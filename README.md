## How to use?

### Add as submodule

``` bash
    cd {project-directory}/src
    git submodule add https://github.com/huhulab/antd-kit.git
    # pull all submodules
    git submodule foreach git pull origin master
```

### Use in your code
``` javascript
    import {
        // form
        FormItem,
        BaseForm,
        SearchForm,
        FormModal,
        formHelpers,
        formRules,
        // table
        TableMixin,
        // other
        PageIntro,
        Topbar,
        PageIntro,
    } from 'antd-kit';
```

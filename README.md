# rowlow.layout.layer-group

This module can eaily be used to create overlays or layerstacks in HTML.

## Install

```
    bower install --save rowlow.layout.layer-group
```

## Variables

```
    $rowlow-layer-group-namespace // Specific module namespace
```


## Usage

### Setup
```
    /* Set modules namespace (optional) */
    $rowlow-layer-group-namespace: "namespace-";

    @import "bower_components/rowlow.layout.layer-group/main.scss"
```


### HTML
```
    <div class="layer-group">
        <img src="http://placehold.it/840x560" alt=""/>
        <div class="layer">[...]</div>
        <div class="layer">[...]</div>
        [...]
    </div>
```


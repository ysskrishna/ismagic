# What is this?

Get perfect shadows every time for the non-designer

# Installation

`npm i ismagic --save`

Then ...

```
import { ismagic } from "ismagic";

ismagic({
    shadow_type: "soft",
    padding: false
});
```

## Options

ismagic supports 2 options, noth of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)
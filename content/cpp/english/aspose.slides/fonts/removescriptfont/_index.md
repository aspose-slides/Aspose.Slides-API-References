---
title: RemoveScriptFont()
second_title: Aspose.Slides for C++ API Reference
description: Removes the font setting associated with a specific script tag from the theme's font collection.
type: docs
weight: 118
url: /aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) method


Removes the font setting associated with a specific script tag from the theme's font collection.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | The BCP-47 script code whose font setting should be removed. |
## Remarks



This example demonstrates how to remove the font mapping for the Hebrew script: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## See Also

* Class [String](../../../system/string/)
* Class [Fonts](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
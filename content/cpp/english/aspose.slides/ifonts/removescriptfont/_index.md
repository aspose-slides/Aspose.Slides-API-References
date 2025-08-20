---
title: RemoveScriptFont()
second_title: Aspose.Slides for C++ API Reference
description: Removes the font setting associated with a specific script tag from the theme's font collection.
type: docs
weight: 118
url: /aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) method


Removes the font setting associated with a specific script tag from the theme's font collection.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
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
* Class [IFonts](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
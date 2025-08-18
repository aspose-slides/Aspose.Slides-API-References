---
title: SetScriptFont()
second_title: Aspose.Slides for C++ API Reference
description: Assigns a font name to a specific script tag, which defines how text of that script will be rendered in the presentation.
type: docs
weight: 105
url: /aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) method


Assigns a font name to a specific script tag, which defines how text of that script will be rendered in the presentation.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | The BCP-47 script code (e.g., \"Arab\", \"Hebr\", \"Hans\") identifying the writing system. |
| fontName | [System::String](../../../system/string/) | The name of the font to assign to the specified script. |
## Remarks



This example shows how to set the font for the Arabic script to \"Segoe UI\": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## See Also

* Class [String](../../../system/string/)
* Class [Fonts](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
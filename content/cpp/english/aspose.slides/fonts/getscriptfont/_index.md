---
title: GetScriptFont()
second_title: Aspose.Slides for C++ API Reference
description: Gets the font name associated with a specific script tag from the presentation theme.
type: docs
weight: 92
url: /aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) method


Gets the font name associated with a specific script tag from the presentation theme.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | The BCP-47 script code (e.g., \"Latn\", \"Cyrl\", \"Jpan\") used to identify a writing system. |

### Return Value

The name of the font used for the specified script, or **null** if the script is not defined.
## Remarks



This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## See Also

* Class [String](../../../system/string/)
* Class [Fonts](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
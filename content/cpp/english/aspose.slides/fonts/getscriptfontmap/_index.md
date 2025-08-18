---
title: GetScriptFontMap()
second_title: Aspose.Slides for C++ API Reference
description: Returns a dictionary of all script font definitions in the presentation.
type: docs
weight: 79
url: /aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() method


Returns a dictionary of all script font definitions in the presentation.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### Return Value

A dictionary mapping script codes to font names.
## Remarks




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [Fonts](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
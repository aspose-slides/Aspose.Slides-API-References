---
title: GetScriptFontMap()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति में सभी स्क्रिप्ट फ़ॉन्ट परिभाषाओं की शब्दकोश लौटाता है।
type: docs
weight: 79
url: /hi/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() मेथड


प्रस्तुति में सभी स्क्रिप्ट फ़ॉन्ट परिभाषाओं की शब्दकोश लौटाता है।

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### रिटर्न वैल्यू

एक शब्दकोश जो स्क्रिप्ट कोड को फ़ॉन्ट नामों से मैप करता है।
## टिप्पणियाँ




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDictionary](../../../system.collections.generic/idictionary/)
* क्लास [String](../../../system/string/)
* क्लास [Fonts](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
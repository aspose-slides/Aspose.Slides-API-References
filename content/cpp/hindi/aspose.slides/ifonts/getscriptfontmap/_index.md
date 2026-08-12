---
title: GetScriptFontMap()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन में सभी स्क्रिप्ट फ़ॉन्ट परिभाषाओं की एक डिक्शनरी लौटाता है।
type: docs
weight: 79
url: /hi/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() विधि


प्रेजेंटेशन में सभी स्क्रिप्ट फ़ॉन्ट परिभाषाओं का एक डिक्शनरी लौटाता है।

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```


### रिटर्न मान

स्क्रिप्ट कोड को फ़ॉन्ट नामों से मैप करने वाला एक डिक्शनरी।
## टिप्पणियाँ




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IDictionary](../../../system.collections.generic/idictionary/)
* क्लास [String](../../../system/string/)
* क्लास [IFonts](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
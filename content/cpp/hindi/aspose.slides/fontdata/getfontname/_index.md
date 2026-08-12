---
title: GetFontName()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: फ़ॉन्ट नाम लौटाता है, थीम संदर्भ को उपयोग किए गए वास्तविक फ़ॉन्ट से बदलते हुए।
type: docs
weight: 27
url: /hi/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) विधि

फ़ॉन्ट नाम लौटाता है, थीम संदर्भ को उपयोग किए गए वास्तविक फ़ॉन्ट से बदलते हुए।

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) से जिसका थीम्ड फ़ॉन्ट नाम लिया जाना चाहिए। कॉलर को सही मान प्रदान करने की ज़िम्मेदारी है। देखें [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### रिटर्न वैल्यू

फ़ॉन्ट नाम।

## देखें भी

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* क्लास [FontData](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
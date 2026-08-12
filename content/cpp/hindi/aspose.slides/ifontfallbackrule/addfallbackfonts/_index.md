---
title: AddFallBackFonts()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट(s) जोड़ता है।
type: docs
weight: 40
url: /hi/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) विधि


FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट(s) जोड़ता है।

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | FallBack के लिये फ़ॉन्ट का नाम या नाम (कॉमा द्वारा विभक्त) |
## टिप्पणियाँ



```cpp
//FantFallBackRule का नया उदाहरण बनाएं
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//नियम में दूसरा फ़ॉन्ट जोड़ें
newRule->AddFallBackFonts(u"MS Gothic");
//नियम में तीसरा और चौथा फ़ॉन्ट जोड़ें
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) विधि


FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट्स जोड़ता है।

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```


### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | FallBack के लिये फ़ॉन्ट का नाम या नाम (कॉमा द्वारा विभक्त) |
## टिप्पणियाँ



```cpp
//FontFallBackRule का नया उदाहरण बनाएं
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//नियम में अतिरिक्त तीन फ़ॉन्ट जोड़ें
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [IFontFallBackRule](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
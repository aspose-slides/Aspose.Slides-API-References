---
title: AddFallBackFonts()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: FallBack फ़ॉन्ट्स की सूची में नया फ़ॉन्ट(s) जोड़ता है।
type: docs
weight: 79
url: /hi/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) मेथड

नए फ़ॉन्ट(s) को FallBack फ़ॉन्ट्स की सूची में जोड़ता है।

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Font's name or names (delimited by comma) for FallBack |
## टिप्पणी

```cpp
// FontFallBackRule का नया इंस्टेंस बनाएं
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//नियम में दूसरा फ़ॉन्ट जोड़ें
newRule->AddFallBackFonts(u"MS Gothic");
//नियम में तीसरा और चौथा फ़ॉन्ट जोड़ें
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) मेथड

नई फ़ॉन्ट्स को FallBack फ़ॉन्ट्स की सूची में जोड़ता है।

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Font's name or names (delimited by comma) for FallBack |
## टिप्पणी

```cpp
//FontFallBackRule का नया इंस्टेंस बनाएं
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//नियम में अतिरिक्त तीन फ़ॉन्ट जोड़ें
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [FontFallBackRule](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
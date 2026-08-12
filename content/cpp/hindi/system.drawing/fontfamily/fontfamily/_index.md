---
title: FontFamily()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट नाम के साथ फ़ॉन्ट फैमिली का प्रतिनिधित्व करने वाली FontFamily class का नया उदाहरण बनाता है।
type: docs
weight: 1
url: /hi/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) कंस्ट्रक्टर

निर्दिष्ट नाम के साथ फ़ॉन्ट फैमिली का प्रतिनिधित्व करने वाली [FontFamily](../) क्लास का नया इंस्टेंस बनाता है।

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | फ़ॉन्ट फैमिली नाम |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) कंस्ट्रक्टर

निर्दिष्ट FontCollection में निर्दिष्ट नाम के साथ [FontFamily](../) का नया इंस्टेंस बनाता है।

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | फ़ॉन्ट फैमिली नाम |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | वह FontCollection जो इस इंस्टेंस को समाहित करता है। |

## FontFamily::FontFamily(Text::GenericFontFamilies) कंस्ट्रक्टर

निर्दिष्ट सामान्य फ़ॉन्ट फैमिली से [FontFamily](../) का नया इंस्टेंस बनाता है।

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | GenericFontFamilies मान जिससे [FontFamily](../) बनाया जाता है। |

## संबंधित देखें

* एन्यूम [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [FontFamily](../)
* क्लास [FontCollection](../../../system.drawing.text/fontcollection/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
---
title: GetScriptFont()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: प्रेज़ेंटेशन थीम से किसी विशिष्ट स्क्रिप्ट टैग से जुड़े फ़ॉन्ट नाम को प्राप्त करता है।
type: docs
weight: 92
url: /hi/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) विधि


प्रीज़ेंटेशन थीम से विशिष्ट स्क्रिप्ट टैग से जुड़े फ़ॉन्ट नाम को प्राप्त करता है।

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 स्क्रिप्ट कोड (जैसे, "Latn", "Cyrl", "Jpan") जो किसी लेखन प्रणाली की पहचान के लिए उपयोग किया जाता है। |

### रिटर्न वैल्यू

निर्देशित स्क्रिप्ट के लिए उपयोग किए गए फ़ॉन्ट का नाम, या **null** यदि स्क्रिप्ट परिभाषित नहीं है।

## टिप्पणियाँ



यह उदाहरण दर्शाता है कि प्रेज़ेंटेशन थीम में सिरिलिक स्क्रिप्ट को सौंपा गया फ़ॉन्ट कैसे प्राप्त किया जाए। 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## संदर्भ

* क्लास [String](../../../system/string/)
* क्लास [IFonts](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
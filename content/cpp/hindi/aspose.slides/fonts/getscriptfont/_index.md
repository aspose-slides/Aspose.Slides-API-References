---
title: GetScriptFont()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: प्रेज़ेंटेशन थीम से विशिष्ट स्क्रिप्ट टैग से जुड़े फ़ॉन्ट नाम को प्राप्त करता है।
type: docs
weight: 92
url: /hi/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) विधि


प्रेज़ेंटेशन थीम से विशिष्ट स्क्रिप्ट टैग से जुड़े फ़ॉन्ट नाम को प्राप्त करता है।

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 स्क्रिप्ट कोड (जैसे, "Latn", "Cyrl", "Jpan") जिसका उपयोग एक लेखन प्रणाली की पहचान करने के लिए किया जाता है। |

### रिटर्न मान

निर्दिष्ट स्क्रिप्ट के लिए उपयोग किए गए फ़ॉन्ट का नाम, या **null** यदि स्क्रिप्ट परिभाषित नहीं है।

## टिप्पणी



यह उदाहरण दर्शाता है कि प्रेज़ेंटेशन थीम में साइरिलिक स्क्रिप्ट को असाइन किया गया फ़ॉन्ट कैसे प्राप्त करें। 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [Fonts](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
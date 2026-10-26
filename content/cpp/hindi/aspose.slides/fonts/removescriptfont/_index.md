---
title: RemoveScriptFont()
second_title: Aspose.Slides for C++ API संदर्भ
description: थीम की फ़ॉन्ट संग्रह से किसी विशिष्ट स्क्रिप्ट टैग से जुड़ी फ़ॉन्ट सेटिंग को हटाता है।
type: docs
weight: 118
url: /hi/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) मेथड

थीम की फ़ॉन्ट संग्रह से किसी विशिष्ट स्क्रिप्ट टैग से जुड़ी फ़ॉन्ट सेटिंग को हटाता है।

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | वह BCP-47 स्क्रिप्ट कोड जिसका फ़ॉन्ट सेटिंग हटाना चाहिए। |

## टिप्पणियाँ

यह उदाहरण यह दर्शाता है कि हेब्रू स्क्रिप्ट के लिए फ़ॉन्ट मैपिंग कैसे हटाएँ:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [Fonts](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
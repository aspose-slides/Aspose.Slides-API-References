---
title: SetScriptFont()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक विशिष्ट स्क्रिप्ट टैग को फ़ॉन्ट नाम असाइन करता है, जो निर्धारित करता है कि प्रस्तुति में उस स्क्रिप्ट का पाठ कैसे प्रदर्शित होगा।
type: docs
weight: 105
url: /hi/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) विधि

एक विशिष्ट स्क्रिप्ट टैग को फ़ॉन्ट नाम सौंपता है, जिससे उस स्क्रिप्ट का पाठ प्रस्तुति में कैसे प्रदर्शित होगा, यह निर्धारित होता है।

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 स्क्रिप्ट कोड (जैसे, "Arab", "Hebr", "Hans") जो लेखन प्रणाली की पहचान करता है। |
| fontName | [System::String](../../../system/string/) | निर्दिष्ट स्क्रिप्ट को सौंपने के लिये फ़ॉन्ट का नाम। |
## टिप्पणियाँ

यह उदाहरण दर्शाता है कि कैसे अरबी लिपि के लिए फ़ॉन्ट "Segoe UI" सेट किया जाए: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [Fonts](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
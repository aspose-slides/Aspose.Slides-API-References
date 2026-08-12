---
title: RemoveScriptFont()
second_title: C++ API रेफ़रेंस के लिए Aspose.Slides
description: थीम के फ़ॉन्ट संग्रह से किसी विशिष्ट स्क्रिप्ट टैग से संबद्ध फ़ॉन्ट सेटिंग को हटाता है।
type: docs
weight: 118
url: /hi/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) विधि

थीम के फ़ॉन्ट संग्रह से किसी विशिष्ट स्क्रिप्ट टैग से संबद्ध फ़ॉन्ट सेटिंग को हटाता है।

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 स्क्रिप्ट कोड जिसका फ़ॉन्ट सेटिंग हटाया जाना चाहिए। |
## टिप्पणी

यह उदाहरण यह दर्शाता है कि हिब्रू स्क्रिप्ट के लिए फ़ॉन्ट मैपिंग को कैसे हटाया जाए:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## देखें

* क्लास [String](../../../system/string/)
* क्लास [IFonts](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
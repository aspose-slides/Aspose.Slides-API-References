---
title: SetScriptFont()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक विशिष्ट स्क्रिप्ट टैग को फ़ॉन्ट नाम असाइन करता है, जो परिभाषित करता है कि प्रस्तुति में उस स्क्रिप्ट का टेक्स्ट कैसे रेंडर होगा।
type: docs
weight: 105
url: /hi/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) method

किसी विशिष्ट स्क्रिप्ट टैग को फ़ॉन्ट नाम असाइन करता है, जिससे उस स्क्रिप्ट का टेक्स्ट प्रस्तुति में कैसे रेंडर किया जाएगा, परिभाषित होता है।

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 स्क्रिप्ट कोड (जैसे "Arab", "Hebr", "Hans") जो लेखन प्रणाली की पहचान करता है। |
| fontName | [System::String](../../../system/string/) | निर्दिष्ट स्क्रिप्ट को असाइन करने के लिए फ़ॉन्ट का नाम। |

## टिप्पणियाँ

यह उदाहरण दिखाता है कि अरबी स्क्रिप्ट के लिए फ़ॉन्ट "Segoe UI" कैसे सेट किया जाए: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## देखें

* क्लास [String](../../../system/string/)
* क्लास [IFonts](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
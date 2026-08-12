---
title: LoadExternalFonts()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: फ़ॉन्ट खोजने के लिए अतिरिक्त फ़ोल्डर जोड़ता है।
type: docs
weight: 1
url: /hi/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) विधि

फ़ॉन्ट खोजने के लिए अतिरिक्त फ़ोल्डर जोड़ता है।

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | अतिरिक्त फ़ॉन्ट पढ़ने के लिए निर्देशिकाएँ। |

## टिप्पणियाँ

निम्न उदाहरण दिखाते हैं कि .TTF से कस्टम फ़ॉन्ट कैसे लोड करें। 
```cpp
// दस्तावेज़ डिरेक्टरी का पथ।
System::String dataDir = u"C:\\";

// फ़ॉन्ट खोजने के लिए फ़ोल्डर
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// कस्टम फ़ॉन्ट डिरेक्टरी के फ़ॉन्ट लोड करें
FontsLoader::LoadExternalFonts(folders);

// कुछ काम करें और प्रेजेंटेशन/स्लाइड्स रेंडरिंग करें
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// फ़ॉन्ट कैश साफ़ करें
FontsLoader::ClearCache();
```

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [FontsLoader](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
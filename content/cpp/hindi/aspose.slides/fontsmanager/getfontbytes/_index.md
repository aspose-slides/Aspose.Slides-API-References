---
title: GetFontBytes()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का प्रतिनिधित्व करने वाला बाइट एरे प्राप्त करता है।
type: docs
weight: 131
url: /hi/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) विधि


निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा का प्रतिनिधित्व करने वाला बाइट एरे प्राप्त करता है।

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | फ़ॉन्ट डेटा ऑब्जेक्ट जिसमें फ़ॉन्ट [IFontData](../../ifontdata/) के बारे में जानकारी होती है। |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | वह फ़ॉन्ट शैली जिसके लिए डेटा प्राप्त किया जाना है [FontStyleType](../../fontstyletype/)। |

### रिटर्न वैल्यू

निर्दिष्ट फ़ॉन्ट शैली के लिए फ़ॉन्ट डेटा वाला बाइट एरे। यदि फ़ॉन्ट डेटा या शैली नहीं मिलती है, तो null लौटाता है।

## टिप्पणियाँ




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## देखें

* एन्युम [FontStyleType](../../fontstyletype/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontData](../../ifontdata/)
* क्लास [FontsManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
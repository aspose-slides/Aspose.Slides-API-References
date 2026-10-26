---
title: GetFontBytes()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए फ़ॉन्ट डेटा को दर्शाने वाला बाइट एरे पुनः प्राप्त करता है।
type: docs
weight: 131
url: /hi/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) विधि

फ़ॉन्ट डेटा को प्रदर्शित करने वाले बाइट एरे को प्राप्त करता है जो निर्दिष्ट फ़ॉन्ट शैली और फ़ॉन्ट डेटा के लिए है।

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | फ़ॉन्ट डेटा ऑब्जेक्ट जिसमें फ़ॉन्ट [IFontData](../../ifontdata/) के बारे में जानकारी होती है। |
| fontStyle | [FontStyleType](../../fontstyletype/) | फ़ॉन्ट की वह शैली जिसके लिए डेटा प्राप्त किया जाना है [FontStyleType](../../fontstyletype/)। |

### वापसी मान

निर्दिष्ट फ़ॉन्ट शैली के लिए फ़ॉन्ट डेटा वाला बाइट एरे। यदि फ़ॉन्ट डेटा या शैली नहीं मिला, तो null लौटाता है।

## टिप्पणियाँ

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## संबंधित देखें

* एन्युम [FontStyleType](../../fontstyletype/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontData](../../ifontdata/)
* क्लास [IFontsManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
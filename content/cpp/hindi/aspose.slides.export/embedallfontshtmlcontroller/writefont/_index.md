---
title: WriteFont()
second_title: Aspose.Slides for C++ API संदर्भ
description: डेटा को base64 के रूप में सीधे HTML दस्तावेज़ में लिखता है
type: docs
weight: 105
url: /hi/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) method

डेटा को base64 रूप में HTML दस्तावेज़ में लिखता है

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML जनरेटर |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | क्रमांकित करने के लिए फ़ॉन्ट |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | प्रतिस्थापित फ़ॉन्ट (यदि फ़ॉन्ट प्रतिस्थापन हुआ हो), अन्यथा null |
| fontStyle | [System::String](../../../system/string/) | फ़ॉन्ट शैली |
| fontWeight | [System::String](../../../system/string/) | फ़ॉन्ट वजन |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | फ़ॉन्ट डेटा |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [IHtmlGenerator](../../ihtmlgenerator/)
* क्लास [IFontData](../../../aspose.slides/ifontdata/)
* क्लास [String](../../../system/string/)
* क्लास [EmbedAllFontsHtmlController](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
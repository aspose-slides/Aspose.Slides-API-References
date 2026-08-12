---
title: ToBase64CharArray()
second_title: Aspose.Slides for C++ API संदर्भ
description: Base-64 निर्दिष्ट बाइट एरे में तत्वों की एक रेंज को एन्कोड करता है और एन्कोड किए गए डेटा को यूनिकोड अक्षरों की एरे के रूप में संग्रहीत करता है।
type: docs
weight: 27
url: /hi/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) विधि

Base-64 निर्दिष्ट बाइट एरे में तत्वों की एक रेंज को एन्कोड करता है और एन्कोड किए गए डेटा को यूनिकोड अक्षरों की एरे के रूप में संग्रहीत करता है।

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | एन्कोड करने के लिए तत्वों की रेंज वाले बाइट्स की एरे |
| offset_in | int | इनपुट एरे में उस तत्व का इंडेक्स जहाँ से एन्कोड करने की रेंज शुरू होती है |
| length | int | एन्कोड करने के लिए तत्वों की रेंज की लंबाई |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | आउटपुट एरे का एक स्थिर रेफ़रेंस जहाँ परिणामी डेटा रखा जाएगा |
| offset_out | int | आउटपुट एरे में वह इंडेक्स जहाँ से परिणामी डेटा रखना शुरू किया जाएगा |
| insert_line_breaks | **bool** | निर्देश देता है कि क्या लाइन ब्रेक वर्ण हर 76 Base-64 अक्षरों के बाद आउटपुट एरे में डाले जाएँ |

### Return Value

आउटपुट एरे में लिखे गए अक्षरों की संख्या

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) विधि

Base-64 निर्दिष्ट बाइट एरे में तत्वों की एक रेंज को एन्कोड करता है और एन्कोड किए गए डेटा को यूनिकोड अक्षरों की एरे के रूप में संग्रहीत करता है।

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | एन्कोड करने के लिए तत्वों की रेंज वाले बाइट्स की एरे |
| offset_in | int | इनपुट एरे में उस तत्व का इंडेक्स जहाँ से एन्कोड करने की रेंज शुरू होती है |
| length | int | एन्कोड करने के लिए तत्वों की रेंज की लंबाई |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | आउटपुट एरे का एक स्थिर रेफ़रेंस जहाँ परिणामी डेटा रखा जाएगा |
| offset_out | int | आउटपुट एरे में वह इंडेक्स जहाँ से परिणामी डेटा रखना शुरू किया जाएगा |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | बेस-64 एन्कोडेड डेटा के फ़ॉर्मेटिंग विकल्प निर्दिष्ट करता है |

### Return Value

आउटपुट एरे में लिखे गए अक्षरों की संख्या

## See Also

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
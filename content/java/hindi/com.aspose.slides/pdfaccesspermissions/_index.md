---
title: PdfAccessPermissions
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: जब दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोला जाता है, तब किन पहुँच अनुमतियों को दिया जाना चाहिए, यह निर्धारित करने वाले फ़्लैग का एक सेट शामिल करता है।
type: docs
url: /hi/com.aspose.slides/pdfaccesspermissions/
---
**विरासत:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

जब दस्तावेज़ को उपयोगकर्ता पहुंच के साथ खोला जाता है, तब कौन-सी पहुँच अनुमतियों को दिया जाना चाहिए, यह निर्धारित करने वाले फ़्लैग का एक सेट शामिल करता है।

## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| [None](#None) | निर्दिष्ट करता है कि उपयोगकर्ता के पास पहुँच अनुमतियाँ नहीं हैं। |
| [PrintDocument](#PrintDocument) | निर्दिष्ट करता है कि क्या उपयोगकर्ता दस्तावेज़ को प्रिंट कर सकता है (संभवतः उच्चतम गुणवत्ता स्तर पर नहीं, यह इस बात पर निर्भर करता है कि बिट [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) भी सेट है या नहीं)। |
| [ModifyContent](#ModifyContent) | निर्दिष्ट करता है कि क्या उपयोगकर्ता दस्तावेज़ की सामग्रियों को उन ऑपरेशनों के द्वारा संशोधित कर सकता है जो बिट्स [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) द्वारा नियंत्रित नहीं हैं। |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | निर्दिष्ट करता है कि क्या उपयोगकर्ता दस्तावेज़ से पाठ और ग्राफ़िक्स को कॉपी या अन्य तरीकों से निकाल सकता है, जो बिट [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) द्वारा नियंत्रित नहीं है। |
| [AddOrModifyFields](#AddOrModifyFields) | निर्दिष्ट करता है कि क्या उपयोगकर्ता पाठ एनोटेशन जोड़ या संशोधित कर सकता है, इंटरैक्टिव फ़ॉर्म फ़ील्ड भर सकता है, और यदि बिट [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) भी सेट है, तो इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) बना या संशोधित कर सकता है। |
| [FillExistingFields](#FillExistingFields) | निर्दिष्ट करता है कि क्या उपयोगकर्ता मौजूदा इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) भर सकता है, चाहे बिट [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) साफ़ हो। |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | निर्दिष्ट करता है कि क्या उपयोगकर्ता अक्षमताओं वाले उपयोगकर्ताओं की पहुँच के लिए या अन्य उद्देश्यों हेतु पाठ और ग्राफ़िक्स निकाल सकता है। |
| [AssembleDocument](#AssembleDocument) | निर्दिष्ट करता है कि क्या उपयोगकर्ता दस्तावेज़ को संयोजित कर सकता है (पृष्ठ सम्मिलित, घुमाना, या हटाना तथा बुकमार्क या थंबनेल छवियां बनाना), चाहे बिट [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) साफ़ हो। |
| [HighQualityPrint](#HighQualityPrint) | निर्दिष्ट करता है कि क्या उपयोगकर्ता दस्तावेज़ को ऐसी प्रस्तुति में प्रिंट कर सकता है जिससे PDF सामग्री की एक विश्वसनीय डिजिटल प्रति बनाई जा सके। |
### None {#None}
```
public static final int None
```

निर्दिष्ट करता है कि उपयोगकर्ता के पास पहुँच अनुमतियाँ नहीं हैं।

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

निर्दिष्ट करता है कि क्या उपयोगकर्ता दस्तावेज़ को प्रिंट कर सकता है (संभवतः उच्चतम गुणवत्ता स्तर पर नहीं, यह इस बात पर निर्भर करता है कि बिट [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) भी सेट है या नहीं)।

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

निर्दिष्ट करता है कि क्या उपयोगकर्ता दस्तावेज़ की सामग्रियों को उन ऑपरेशनों के द्वारा संशोधित कर सकता है जो बिट्स [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) द्वारा नियंत्रित नहीं हैं।

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

निर्दिष्ट करता है कि क्या उपयोगकर्ता दस्तावेज़ से पाठ और ग्राफ़िक्स को कॉपी या अन्य तरीकों से निकाल सकता है, जो बिट [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) द्वारा नियंत्रित नहीं है।

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

निर्दिष्ट करता है कि क्या उपयोगकर्ता पाठ एनोटेशन जोड़ या संशोधित कर सकता है, इंटरैक्टिव फ़ॉर्म फ़ील्ड भर सकता है, और यदि बिट [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) भी सेट है, तो इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) बना या संशोधित कर सकता है।

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

निर्दिष्ट करता है कि क्या उपयोगकर्ता मौजूदा इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) भर सकता है, चाहे बिट [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) साफ़ हो।

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

निर्दिष्ट करता है कि क्या उपयोगकर्ता अक्षमताओं वाले उपयोगकर्ताओं की पहुँच के लिए या अन्य उद्देश्यों हेतु पाठ और ग्राफ़िक्स निकाल सकता है।

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

निर्दिष्ट करता है कि क्या उपयोगकर्ता दस्तावेज़ को संयोजित कर सकता है (पृष्ठ सम्मिलित, घुमाना, या हटाना तथा बुकमार्क या थंबनेल छवियां बनाना), चाहे बिट [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) साफ़ हो।

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

निर्दिष्ट करता है कि क्या उपयोगकर्ता दस्तावेज़ को ऐसी प्रस्तुति में प्रिंट कर सकता है जिससे PDF सामग्री की एक विश्वसनीय डिजिटल प्रति बनाई जा सके। जब यह बिट साफ़ हो (और बिट [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) सेट हो), तो प्रिंटिंग को स्वरूप के निम्न-स्तरीय प्रतिनिधित्व तक सीमित किया जाता है, संभवतः गुणवत्ता में घटाव के साथ।
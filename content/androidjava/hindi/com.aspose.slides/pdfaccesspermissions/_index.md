---
title: PdfAccessPermissions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: जब दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोला जाता है तो किन पहुँच अनुमतियों को प्रदान किया जाना चाहिए यह निर्दिष्ट करने वाले फ़्लैग्स का एक सेट सम्मिलित करता है।
type: docs
url: /hi/com.aspose.slides/pdfaccesspermissions/
---
**विरासत:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Contains a set of flags specifying which access permissions should be granted when the document is opened with user access.

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [None](#None) | निर्दिष्ट करता है कि उपयोगकर्ता के पास पहुँच अनुमतियाँ नहीं हैं। |
| [PrintDocument](#PrintDocument) | निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ को प्रिंट कर सकता है या नहीं (संभवतः उच्चतम गुणवत्ता स्तर पर नहीं, यह इस पर निर्भर करता है कि बिट [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) भी सेट है या नहीं)। |
| [ModifyContent](#ModifyContent) | निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ की सामग्री को उन कार्यों द्वारा संशोधित कर सकता है जो बिट्स [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) द्वारा नियंत्रित नहीं हैं। |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ से टेक्स्ट और ग्राफ़िक्स को उस बिट [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) द्वारा नियंत्रित कार्यों के अलावा अन्य कार्यों द्वारा कॉपी या निकाल सकता है। |
| [AddOrModifyFields](#AddOrModifyFields) | निर्दिष्ट करता है कि उपयोगकर्ता टेक्स्ट एनोटेशन जोड़ या संशोधित कर सकता है, इंटरैक्टिव फ़ॉर्म फ़ील्ड भर सकता है, और यदि बिट [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) भी सेट है, तो इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) बना या संशोधित कर सकता है। |
| [FillExistingFields](#FillExistingFields) | निर्दिष्ट करता है कि उपयोगकर्ता मौजूदा इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) भर सकता है, भले ही बिट [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) साफ़ हो। |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | निर्दिष्ट करता है कि उपयोगकर्ता विकलांग उपयोगकर्ताओं की पहुँच के समर्थन या अन्य उद्देश्यों के लिए टेक्स्ट और ग्राफ़िक्स को निकाल सकता है। |
| [AssembleDocument](#AssembleDocument) | निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ को (पृष्ठों को सम्मिलित, घुमाने या हटाने और बुकमार्क या थंबनेल चित्र बनाने) असेंबल कर सकता है, भले ही बिट [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) साफ़ हो। |
| [HighQualityPrint](#HighQualityPrint) | निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ को ऐसी प्रस्तुति में प्रिंट कर सकता है जिससे PDF सामग्री की सटीक डिजिटल कॉपी बनाई जा सके। |

### None {#None}
```
public static final int None
```

निर्दिष्ट करता है कि उपयोगकर्ता के पास पहुँच अनुमतियाँ नहीं हैं।

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ को प्रिंट कर सकता है या नहीं (संभवतः उच्चतम गुणवत्ता स्तर पर नहीं, यह इस पर निर्भर करता है कि बिट [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) भी सेट है या नहीं)।

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ की सामग्री को उन कार्यों द्वारा संशोधित कर सकता है जो बिट्स [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) द्वारा नियंत्रित नहीं हैं।

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ से टेक्स्ट और ग्राफ़िक्स को उस बिट [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) द्वारा नियंत्रित कार्यों के अलावा अन्य कार्यों द्वारा कॉपी या निकाल सकता है।

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

निर्दिष्ट करता है कि उपयोगकर्ता टेक्स्ट एनोटेशन जोड़ या संशोधित कर सकता है, इंटरैक्टिव फ़ॉर्म फ़ील्ड भर सकता है, और यदि बिट [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) भी सेट है, तो इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) बना या संशोधित कर सकता है।

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

निर्दिष्ट करता है कि उपयोगकर्ता मौजूदा इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) भर सकता है, भले ही बिट [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) साफ़ हो।

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

निर्दिष्ट करता है कि उपयोगकर्ता विकलांग उपयोगकर्ताओं की पहुँच के समर्थन या अन्य उद्देश्यों के लिए टेक्स्ट और ग्राफ़िक्स को निकाल सकता है।

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ को (पृष्ठों को सम्मिलित, घुमाने या हटाने और बुकमार्क या थंबनेल चित्र बनाने) असेंबल कर सकता है, भले ही बिट [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) साफ़ हो।

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ को ऐसी प्रस्तुति में प्रिंट कर सकता है जिससे PDF सामग्री की सटीक डिजिटल कॉपी बनाई जा सके। जब यह बिट साफ़ हो (और बिट [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) सेट हो), तो प्रिंटिंग को दिखावट के निम्न-स्तरीय प्रतिनिधित्व तक सीमित किया जाता है, संभवतः घटित गुणवत्ता के साथ।
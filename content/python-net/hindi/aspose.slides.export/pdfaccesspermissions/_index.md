---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions एन्यूमरेशन

एक सेट फ़्लैग सम्मिलित करता है जो यह निर्दिष्ट करता है कि दस्तावेज़ को उपयोगकर्ता एक्सेस के साथ खोले जाने पर कौन-सी एक्सेस अनुमतियाँ प्रदान की जानी चाहिए।

PdfAccessPermissions प्रकार नीचे दिए गए सदस्यों को उजागर करता है:

## फ़ील्ड

| Field | Description |
| :- | :- |
| NONE | निर्दिष्ट करता है कि उपयोगकर्ता के पास कोई एक्सेस अनुमति नहीं है। |
| PRINT_DOCUMENT | निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ को प्रिंट कर सकता है (संभवतः सर्वोच्च गुणवत्ता स्तर पर नहीं, यह इस बात पर निर्भर करता है कि <br/>            बिट [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) भी सेट है या नहीं)। |
| MODIFY_CONTENT | निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ की सामग्री को उन संचालन द्वारा संशोधित कर सकता है जो<br/>            बिट्स [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT) द्वारा नियंत्रित नहीं हैं। |
| COPY_TEXT_AND_GRAPHICS | निर्दिष्ट करता है कि उपयोगकर्ता टेक्स्ट और ग्राफ़िक्स को कॉपी या अन्यथा निकाल सकता है जो<br/>            बिट [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS) द्वारा नियंत्रित नहीं हैं। |
| ADD_OR_MODIFY_FIELDS | निर्दिष्ट करता है कि उपयोगकर्ता टेक्स्ट एनोटेशन जोड़ या संशोधित कर सकता है, इंटरैक्टिव फ़ॉर्म फ़ील्ड भर सकता है, और यदि बिट<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) भी सेट है, तो इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) बना या संशोधित कर सकता है। |
| FILL_EXISTING_FIELDS | निर्दिष्ट करता है कि उपयोगकर्ता मौजूदा इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ीールド सहित) भर सकता है, भले ही बिट<br/>            [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) साफ़ हो। |
| EXTRACT_TEXT_AND_GRAPHICS | निर्दिष्ट करता है कि उपयोगकर्ता विकलांग उपयोगकर्ताओं के लिए पहुंच क्षमताओं के समर्थन में या अन्य उद्देश्यों के लिए टेक्स्ट और ग्राफ़िक्स निकाल सकता है<br/>            या अन्य उद्देश्यों के लिए। |
| ASSEMBLE_DOCUMENT | निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ को (पृष्ठ जोड़ना, घुमाना, या हटाना और बुकमार्क या<br/>            थंबनेल छवियां बनाना) संकलित कर सकता है, भले ही बिट [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) साफ़ हो। |
| HIGH_QUALITY_PRINT | निर्दिष्ट करता है कि उपयोगकर्ता दस्तावेज़ को ऐसी प्रस्तुति से प्रिंट कर सकता है जिससे PDF सामग्री की एक सटीक डिजिटल प्रति生成 की जा सके। जब यह बिट साफ़ हो (और बिट [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/hi/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) सेट हो),<br/>            प्रिंटिंग को दिखावट के एक निम्न-स्तरीय प्रतिनिधित्व तक सीमित किया जाता है, संभवतः घटी हुई गुणवत्ता के साथ। |

### देखें
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* पुस्तकालय [`Aspose.Slides`](/slides/python-net)
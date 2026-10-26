---
title: get_Encoding()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: XML दस्तावेज़ की एन्कोडिंग स्तर को लौटाता है।
type: docs
weight: 14
url: /hi/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() मेथड

XML दस्तावेज़ की एनकोडिंग स्तर को लौटाता है।

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### रिटर्न मान

मान्य अक्षर एनकोडिंग नाम।

## टिप्पणी

XML के लिए सबसे अधिक सामान्यतः समर्थित अक्षर एनकोडिंग नाम निम्नलिखित हैं:

| श्रेणी | एनकोडिंग नाम |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

यह मान वैकल्पिक है। यदि कोई मान सेट नहीं किया गया है, तो यह मेथड [String::Empty](../../../system/string/empty/) लौटाता है। यदि एनकोडिंग एट्रीब्यूट शामिल नहीं किया गया है, तो दस्तावेज़ को लिखते या सहेजते समय UTF-8 एनकोडिंग को मान लिया जाता है।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [XmlDeclaration](../)
* नामस्थान [System::Xml](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
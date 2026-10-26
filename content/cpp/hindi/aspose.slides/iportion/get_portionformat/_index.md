---
title: get_PortionFormat()
second_title: Aspose.Slides for C++ API संदर्भ
description: फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है जिसमें टेक्स्ट भाग के स्पष्ट रूप से सेट फ़ॉर्मेटिंग गुण होते हैं, जिसमें कोई विरासत लागू नहीं की गई है। केवल पढ़ने योग्य IPortionFormat.
type: docs
weight: 1
url: /hi/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() विधि

फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है जिसमें उस टेक्स्ट भाग के स्पष्ट रूप से सेट फ़ॉर्मेटिंग गुण होते हैं, जिसमें कोई विरासत लागू नहीं की गई है। केवल पढ़ने योग्य [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## टिप्पणी

फ़ॉर्मेटिंग ऑब्जेक्ट में केवल वर्तमान भाग के लिए परिभाषित फ़ॉर्मेटिंग पैरामीटर होते हैं, विरासत में मिला डेटा लागू नहीं किया जाता।

विरासत में मिले मानों सहित प्रभावी मान प्राप्त करने के लिए [IPortionFormat::GetEffective](../../iportionformat/geteffective/) विधि का उपयोग करें।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IPortionFormat](../../iportionformat/)
* क्लास [IPortion](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
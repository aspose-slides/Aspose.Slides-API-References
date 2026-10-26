---
title: get_PortionFormat()
second_title: Aspose.Slides for C++ API संदर्भ
description: वह फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है जिसमें स्पष्ट रूप से सेट किए गए फ़ॉर्मेटिंग प्रॉपर्टी शामिल होते हैं, जिसका टेक्स्ट भाग में कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य IPortionFormat.
type: docs
weight: 1
url: /hi/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() विधि

टेक्स्ट भाग के स्पष्ट रूप से सेट फ़ॉर्मेटिंग प्रॉपर्टी को सम्मिलित करने वाला फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है, जिसमें कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [IPortionFormat](../../iportionformat/)।

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## टिप्पणी

फ़ॉर्मेटिंग ऑब्जेक्ट केवल वर्तमान भाग के लिए परिभाषित फ़ॉर्मेटिंग पैरामीटर को सम्मिलित करता है, विरासत में मिली डेटा लागू नहीं होती।

विरासत वाले मानों सहित प्रभावी मान प्राप्त करने के लिए [PortionFormat::GetEffective](../../portionformat/geteffective/) विधि का प्रयोग करें।

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IPortionFormat](../../iportionformat/)
* क्लास [Portion](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
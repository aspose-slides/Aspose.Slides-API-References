---
title: set_NumberFormat()
second_title: C++ के लिये Aspose.Slides API संदर्भ
description: "DataLabels ऑब्जेक्ट के लिए स्वरूप स्ट्रिंग का प्रतिनिधित्व करता है। लिखें System::String।"
type: docs
weight: 40
url: /hi/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) विधि

DataLabels ऑब्जेक्ट के लिए स्वरूप स्ट्रिंग का प्रतिनिधित्व करता है। लिखें [System::String](../../../system/string/)।

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## टिप्पणी

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

यदि इस [DataLabelFormat](../) ऑब्जेक्ट का मूल [DataLabelCollection](../../datalabelcollection/) डेटा लेबल्स का संग्रह है, तो यह प्रॉपर्टी [DataLabelCollection](../../datalabelcollection/) संग्रह में नए डेटा लेबल्स के लिए NumberFormat प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। जब इस प्रॉपर्टी को मान के साथ सेट किया जाता है, तो वह मान [DataLabelCollection](../../datalabelcollection/) संग्रह में सभी डेटा लेबल्स के लिए NumberFormat प्रॉपर्टी के लिए भी सेट हो जाता है (उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" सभी DataLabels[i].NumberFormat को val के बराबर बनाता है)।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [DataLabelFormat](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
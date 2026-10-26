---
title: get_NumberFormat()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: "DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। पढ़ें System::String."
type: docs
weight: 27
url: /hi/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() विधि

DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। पढ़ें [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## टिप्पणियाँ


```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```


यदि इस [DataLabelFormat](../) ऑब्जेक्ट का पैरेंट एक [DataLabelCollection](../../datalabelcollection/) डेटा लेबल्स संग्रह है, तो यह प्रॉपर्टी [DataLabelCollection](../../datalabelcollection/) संग्रह में नए डेटा लेबल्स के लिए NumberFormat प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। जब इस प्रॉपर्टी को किसी मान से सेट किया जाता है, तो वह मान [DataLabelCollection](../../datalabelcollection/) संग्रह में सभी डेटा लेबल्स की NumberFormat प्रॉपर्टी के लिए भी सेट हो जाता है (उदाहरण के लिए \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" सभी DataLabels[i].NumberFormat को val के बराबर बनाता है)।

## देखें

* क्लास [String](../../../system/string/)
* क्लास [DataLabelFormat](../)
* नामस्थान [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
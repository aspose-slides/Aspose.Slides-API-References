---
title: get_NumberFormat()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग को दर्शाता है। पढ़ें System::String."
type: docs
weight: 27
url: /hi/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() मेथड


DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग को दर्शाता है। पढ़ें [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## टिप्पणियाँ


```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



यदि इस [DataLabelFormat](../../datalabelformat/) ऑब्जेक्ट का पैरेंट [DataLabelCollection](../../datalabelcollection/) डेटा लेबल्स का संग्रह है, तो यह प्रॉपर्टी [DataLabelCollection](../../datalabelcollection/) संग्रह में नए डेटा लेबल्स के लिए NumberFormat प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त करती है या सेट करती है। जब इस प्रॉपर्टी को किसी मान से सेट किया जाता है, तो वह मान [DataLabelCollection](../../datalabelcollection/) संग्रह में सभी डेटा लेबल्स के लिए NumberFormat प्रॉपर्टी पर भी लागू हो जाता है (उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" सभी DataLabels[i].NumberFormat को val के बराबर बनाता है)। 

## देखें

* क्लास [String](../../../system/string/)
* क्लास [IDataLabelFormat](../)
* नामस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
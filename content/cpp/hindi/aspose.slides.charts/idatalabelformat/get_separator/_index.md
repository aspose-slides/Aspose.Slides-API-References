---
title: get_Separator()
second_title: Aspose.Slides for C++ API संदर्भ
description: "सेट करता है या वापस करता है एक Variant जो चार्ट पर डेटा लेबल के लिए उपयोग किए जाने वाले Separator का प्रतिनिधित्व करता है। पढ़ें System::String."
type: docs
weight: 326
url: /hi/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() विधि

सेट करता है या वापस करता है एक Variant जो चार्ट पर डेटा लेबल के लिए उपयोग किए जाने वाले Separator का प्रतिनिधित्व करता है। पढ़ें [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## टिप्पणी

यदि इस [DataLabelFormat](../../datalabelformat/) ऑब्जेक्ट का पैरेंट एक [DataLabelCollection](../../datalabelcollection/) डेटा लेबलों का संग्रह है तो यह प्रॉपर्टी [DataLabelCollection](../../datalabelcollection/) संग्रह में नए डेटा लेबलों के लिए Separator प्रॉपर्टी का डिफॉल्ट मान प्राप्त करती है या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान [DataLabelCollection](../../datalabelcollection/) संग्रह में सभी डेटा लेबलों के लिए Separator प्रॉपर्टी पर भी सेट हो जाता है (उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.Separator = val;" कारण कि सभी DataLabels[i].Separator बराबर val हो जाता है)।

## देखें भी

* क्लास [String](../../../system/string/)
* क्लास [IDataLabelFormat](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
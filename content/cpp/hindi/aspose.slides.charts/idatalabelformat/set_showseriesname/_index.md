---
title: set_ShowSeriesName()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक बूलियन सेट करता है जो चार्ट पर डेटा लेबल्स के लिए श्रृंखला नाम प्रदर्शन व्यवहार को दर्शाता है। श्रृंखला नाम दिखाने के लिए True। छिपाने के लिए False। लिखें bool.
type: docs
weight: 183
url: /hi/aspose.slides.charts/idatalabelformat/set_showseriesname/
---
## IDataLabelFormat::set_ShowSeriesName(bool) विधि

डेटा लेबल्स पर चार्ट में श्रृंखला नाम डिस्प्ले व्यवहार को दर्शाने के लिए एक Boolean सेट करता है। श्रृंखला नाम दिखाने के लिए True। छिपाने के लिए False। लिखें **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowSeriesName(bool value)=0
```

## टिप्पणी

यदि इस [DataLabelFormat](../../datalabelformat/) ऑब्जेक्ट का पैरेंट एक [DataLabelCollection](../../datalabelcollection/) संग्रह है जिसमें डेटा लेबल्स हैं तो यह प्रॉपर्टी [DataLabelCollection](../../datalabelcollection/) संग्रह में नए डेटा लेबल्स के लिए ShowSeriesName प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से यह मान सभी डेटा लेबल्स के ShowSeriesName प्रॉपर्टी में भी सेट हो जाता है [DataLabelCollection](../../datalabelcollection/) संग्रह में (उदाहरण के लिए \"DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;\" कारण सभी DataLabels[i].ShowSeriesName बराबर val हो जाता है)।

## देखें

* क्लास [IDataLabelFormat](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
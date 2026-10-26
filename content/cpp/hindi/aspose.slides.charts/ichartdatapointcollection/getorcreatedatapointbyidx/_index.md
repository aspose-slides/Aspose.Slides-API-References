---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "यदि संग्रह में पहले से ही index सूचकांक वाला डेटा पॉइंट मौजूद है तो वह डेटा पॉइंट लौटाता है। यदि संग्रह में index ==N वाला डेटा पॉइंट नहीं है (जब इस संग्रह में डेटा पॉइंट्स की संख्या N से कम या बराबर हो) तो अभावपूर्ण डेटा पॉइंट्स जोड़ता है और अंतिम (जिसका अनुरोधित सूचकांक है) लौटाता है। उदाहरण के लिए, संग्रह के सूचकांक {0, 1, 2} हैं, और अनुरोधित सूचकांक 5 है। तब मेथड अभावपूर्ण डेटा पॉइंट्स जोड़ता है: {0, 1, 2, 3, 4, 5}। और सूचकांक 5 वाला डेटा पॉइंट लौटाता है।"
type: docs
weight: 131
url: /hi/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) विधि


यदि संग्रह में पहले से ही *index* सूचकांक वाला डेटा पॉइंट मौजूद है तो वह डेटा पॉइंट लौटाता है। यदि संग्रह में *index* ==N (जब इस संग्रह में डेटा पॉइंट्स की संख्या N से कम या बराबर हो) वाला डेटा पॉइंट नहीं है तो अधूरा डेटा पॉइंट्स जोड़ता है और अंतिम (जिसका अनुरोधित सूचकांक है) लौटाता है। उदाहरण के लिए, संग्रह के सूचकांक {0, 1, 2} हैं, और अनुरोधित सूचकांक 5 है। तब मेथड अधूरा डेटा पॉइंट्स जोड़ता है: {0, 1, 2, 3, 4, 5}। और सूचकांक 5 वाला डेटा पॉइंट लौटाता है।

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| index | **uint32_t** | सूचकांक। |

### रिटर्न मान

अनुरोधित सूचकांक के साथ डेटा पॉइंट लौटाता है।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataPoint](../../ichartdatapoint/)
* क्लास [IChartDataPointCollection](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
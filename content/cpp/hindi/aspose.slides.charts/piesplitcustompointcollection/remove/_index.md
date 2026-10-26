---
title: Remove()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह से आइटम को हटाता है।
type: docs
weight: 79
url: /hi/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) विधि

संग्रह से आइटम को हटाता है।

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | हटाने के लिए डेटा बिंदु। |

### वापसी मान

true यदि आइटम सफलतापूर्वक हटा दिया गया हो; अन्यथा false। यह विधि तब भी false लौटाती है जब आइटम [System::Collections::Generic::List](../../../system.collections.generic/list/){T} में नहीं मिला।

## PieSplitCustomPointCollection::Remove(int32_t) विधि

पैरेंट श्रृंखला बिंदुओं संग्रह में उसके सूचकांक द्वारा संग्रह से आइटम को हटाता है।

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataPointIndex | **int32_t** | पैरेंट श्रृंखला बिंदुओं संग्रह में डेटा बिंदु का सूचकांक। |

## देखें भी

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IChartDataPoint](../../ichartdatapoint/)
* क्लास [PieSplitCustomPointCollection](../)
* नेमस्पेस [Aspose::Slides::Charts](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
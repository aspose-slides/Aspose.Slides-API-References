---
title: GetChildRows()
second_title: Aspose.Slides C++ API रेफ़रेंस
description: निर्दिष्ट संबंध के माध्यम से बच्चे मानी जाने वाली पंक्तियों को प्राप्त करता है।
type: docs
weight: 27
url: /hi/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) विधि


निर्दिष्ट संबंध के माध्यम से बच्चे माने जाने वाली पंक्तियों को प्राप्त करता है।

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | पेरेंट पंक्ति - चाइल्ड पंक्ति संबंध को निर्दिष्ट करने के लिए रिलेशन ऑब्जेक्ट। |

### रिटर्न वैल्यू

[Array](../../../system/array/) चाइल्ड पंक्तियों की प्राप्ति का।

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [DataRow](../)
* क्लास [DataRelation](../../datarelation/)
* नेमस्पेस [System::Data](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
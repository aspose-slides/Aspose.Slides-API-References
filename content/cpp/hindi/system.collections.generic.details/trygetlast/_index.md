---
title: TryGetLast()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संग्रह के अंतिम तत्व को प्राप्त करने का प्रयास करता है।
type: docs
weight: 261
url: /hi/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) फ़ंक्शन

संग्रह के अंतिम तत्व को प्राप्त करने का प्रयास करता है।

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | संग्रह तत्वों का प्रकार। |

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | जिस संग्रह से एक तत्व प्राप्त किया जाना है। |
| found | **bool**\& | आउटपुट पैरामीटर। जब संग्रह में कोई भी तत्व होता है तो true लौटाता है। अन्यथा false लौटाया जाता है। |

### वापसी मान

संग्रह का अंतिम तत्व लौटाता है। जब संग्रह खाली हो तो प्रकार का डिफ़ॉल्ट मान लौटाया जाएगा।

## देखें

* क्लास [IEnumerable](../../system.collections.generic/ienumerable/)
* नामस्थान [System::Collections::Generic::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)
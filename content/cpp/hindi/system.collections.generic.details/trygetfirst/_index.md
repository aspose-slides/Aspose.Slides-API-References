---
title: TryGetFirst()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: संग्रह का पहला तत्व प्राप्त करने की कोशिश करता है।
type: docs
weight: 248
url: /hi/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) function


संग्रह का पहला तत्व प्राप्त करने की कोशिश करता है।

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | संग्रह के तत्वों का प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | संग्रह जिससे एक तत्व प्राप्त किया जाना है। |
| found | **bool**\& | आउटपुट पैरामीटर। जब संग्रह में कोई भी तत्व हो तो true लौटाता है। अन्यथा false लौटाया जाता है। |

### वापसी मान

पहला संग्रह तत्व लौटाता है। जब संग्रह ख़ाली हो तो प्रकार का डिफ़ॉल्ट मान लौटाया जाएगा।

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) function


संग्रह का पहला तत्व प्राप्त करने की कोशिश करता है, जो प्रेडिकेट फ़ंक्शन को संतुष्ट करता है।

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | संग्रह के तत्वों का प्रकार। |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | संग्रह जिससे एक तत्व प्राप्त किया जाना है। |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | प्रेडिकेट फ़ंक्शन। |
| found | **bool**\& | आउटपुट पैरामीटर। जब संग्रह में कोई भी तत्व हो तो true लौटाता है। अन्यथा false लौटाया जाता है। |

### वापसी मान

पहला संग्रह तत्व लौटाता है। जब निर्दिष्ट प्रेडिकेट फ़ंक्शन को संतुष्ट करने वाला कोई तत्व नहीं मिलता है तो प्रकार का डिफ़ॉल्ट मान लौटाया जाएगा।

## संबंधित देखें

* क्लास [IEnumerable](../../system.collections.generic/ienumerable/)
* क्लास [Func](../../system/func/)
* नेमस्पेस [System::Collections::Generic::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)
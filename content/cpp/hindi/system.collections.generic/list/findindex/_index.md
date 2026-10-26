---
title: FindIndex()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: विशिष्ट प्रेडिकेट का पालन करने वाले तत्व की तलाश करता है।
type: docs
weight: 404
url: /hi/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) मेथड

Looks for element adhering to specific predicate.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | तत्वों की जाँच के लिए प्रेडिकेट। |

### वापसी मान

[Index](../../../system/index/) मिलते हुए तत्व का या -1 यदि नहीं मिला।

## List::FindIndex(int, System::Predicate\<T\>) मेथड

Looks for element adhering to specific predicate.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) से खोज शुरू करने के लिए। |
| match | [System::Predicate](../../../system/predicate/)\<T\> | तत्वों की जाँच के लिए प्रेडिकेट। |

### वापसी मान

[Index](../../../system/index/) मिलते हुए तत्व का या -1 यदि नहीं मिला।

## List::FindIndex(int, int, System::Predicate\<T\>) मेथड

Looks for element adhering to specific predicate.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | int | [Index](../../../system/index/) से खोज शुरू करने के लिए। |
| count | int | देखे जाने वाले तत्वों की संख्या। |
| match | [System::Predicate](../../../system/predicate/)\<T\> | तत्वों की जाँच के लिए प्रेडिकेट। |

### वापसी मान

[Index](../../../system/index/) मिलते हुए तत्व का या -1 यदि नहीं मिला।

## संबंधित देखें

* टाइपडिफ़ [Predicate](../../../system/predicate/)
* क्लास [List](../)
* नेमस्पेस [System::Collections::Generic](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
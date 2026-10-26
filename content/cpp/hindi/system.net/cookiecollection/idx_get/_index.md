---
title: idx_get()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट सूचकांक पर कुकी संग्रह से एक कुकी लौटाता है।
type: docs
weight: 40
url: /hi/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) विधि


निर्दिष्ट सूचकांक पर कुकी संग्रह से एक कुकी लौटाता है।

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | **int32_t** | वापस किए जाने वाले कुकी का सूचकांक। |

### रिटर्न मान

निर्दिष्ट सूचकांक पर एक कुकी।

## CookieCollection::idx_get(String) विधि


निर्दिष्ट नाम द्वारा कुकी संग्रह से एक कुकी लौटाता है।

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```


### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| name | [String](../../../system/string/) | वापस किए जाने वाले कुकी का नाम। |

### रिटर्न मान

जब पाया जाए तब निर्दिष्ट नाम द्वारा कुकी संग्रह से एक कुकी, अन्यथा nullptr।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Cookie](../../cookie/)
* Class [CookieCollection](../)
* Class [String](../../../system/string/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
---
title: cbegin()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक अंतर्निहित संग्रह की cbegin() मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो और उसमें cbegin() मेथड हो।
type: docs
weight: 404
url: /hi/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const मेथड

Accessor for [cbegin()](./) मेथड of an underling collection. Only compiles if SmartPtr_ is specialization type with [cbegin()](./) मेथड.

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### रिटर्न मान

संग्रह की शुरुआत का इटरेटर

## संबंधित देखें

* क्लास [SmartPtr](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
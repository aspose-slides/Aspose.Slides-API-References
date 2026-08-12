---
title: end()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अंतर्निहित संग्रह के end() मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ वह विशेषीकरण प्रकार हो जिसमें end() मेथड हो।
type: docs
weight: 391
url: /hi/system/smartptr/end/
---
## SmartPtr::end() मेथड

एक्सेसर के लिए [end()](./) मेथड एक अंतर्निहित संग्रह का। केवल तब ही संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार है जिसके साथ [end()](./) मेथड।

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```

### रिटर्न वैल्यू

इटेरेटर जो संग्रह के अंत की ओर इशारा करता है

## SmartPtr::end() const मेथड

एक्सेसर के लिए [end()](./) मेथड एक अंतर्निहित संग्रह का। केवल तब ही संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार है जिसके साथ [end()](./) मेथड।

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```

### रिटर्न वैल्यू

इटेरेटर जो संग्रह के अंत की ओर इशारा करता है

## संबंधित देखें

* क्लास [SmartPtr](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
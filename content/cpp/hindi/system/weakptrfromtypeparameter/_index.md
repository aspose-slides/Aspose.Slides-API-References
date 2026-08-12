---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ट्रेट संरचना जो तर्क प्रकार को weak-pointer में बदलती है, यदि वह पॉइंटर प्रकार है।
type: docs
weight: 2016
url: /hi/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct


ट्रेट संरचना जो तर्क प्रकार को weak-pointer में बदलती है, यदि वह पॉइंटर प्रकार है।

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)
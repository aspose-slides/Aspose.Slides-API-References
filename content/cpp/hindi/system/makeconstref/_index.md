---
title: MakeConstRef
second_title: Aspose.Slides for C++ API संदर्भ
description: जेनरिक प्रकार \"const reference\" बनाने के लिए ट्रेट, यदि यह String या SmartPtr<> प्रकार है।
type: docs
weight: 1769
url: /hi/system/makeconstref/
---
## MakeConstRef struct

जनरिक प्रकार को \"const reference\" बनाने के लिए ट्रेट, यदि यह [String](../string/) या SmartPtr<> प्रकार है।

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)
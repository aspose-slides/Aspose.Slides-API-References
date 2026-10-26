---
title: IsDBNull()
second_title: Aspose.Slides for C++ API 참조
description: 구현되지 않음.
type: docs
weight: 14
url: /ko/system/convert/isdbnull/
---
## Convert::IsDBNull(const T\&) 메서드


구현되지 않음.

```cpp
template<typename T> static std::enable_if_t<!IsSmartPtr<T>::value, bool> System::Convert::IsDBNull(const T &)
```


## Convert::IsDBNull(const SharedPtr\<T\>\&) 메서드


구현되지 않음 가짜 구현, 값이 nullptr인지 확인합니다.

```cpp
template<typename T> static bool System::Convert::IsDBNull(const SharedPtr<T> &value)
```

## 참조

* Typedef [SharedPtr](../../sharedptr/)
* Struct [IsSmartPtr](../../issmartptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
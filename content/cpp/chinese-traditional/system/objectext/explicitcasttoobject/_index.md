---
title: ExplicitCastToObject()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 235
url: /zh-hant/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) 方法




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) 方法




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## 另見

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [Object](../../object/)
* 類別 [ObjectExt](../)
* 結構 [IsBoxable](../../isboxable/)
* 結構 [IsSmartPtr](../../issmartptr/)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)
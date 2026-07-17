---
title: ExplicitCastToObject()
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 235
url: /zh/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) 方法


```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) 方法


```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## 参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Object](../../object/)
* 类 [ObjectExt](../)
* 结构体 [IsBoxable](../../isboxable/)
* 结构体 [IsSmartPtr](../../issmartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)
---
title: ExplicitCastToObject()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 235
url: /ja/system/objectext/explicitcasttoobject/
---
## ObjectExt::ExplicitCastToObject(const T\&) メソッド




```cpp
template<typename T> static std::enable_if<System::IsBoxable<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## ObjectExt::ExplicitCastToObject(const T\&) メソッド




```cpp
template<typename T> static std::enable_if<System::IsSmartPtr<T>::value, System::SharedPtr<System::Object>>::type System::ObjectExt::ExplicitCastToObject(const T &value)
```

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [Object](../../object/)
* クラス [ObjectExt](../)
* 構造体 [IsBoxable](../../isboxable/)
* 構造体 [IsSmartPtr](../../issmartptr/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)
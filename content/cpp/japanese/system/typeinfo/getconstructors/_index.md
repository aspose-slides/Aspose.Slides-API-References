---
title: GetConstructors()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された BindingFlags を使用して、現在の Type に定義されたコンストラクタを検索します。
type: docs
weight: 365
url: /ja/system/typeinfo/getconstructors/
---
## TypeInfo::GetConstructors(System::Reflection::BindingFlags) const メソッド


現在の Type に定義されたコンストラクタを検索し、指定された BindingFlags を使用します。

```cpp
ArrayPtr<SharedPtr<System::Reflection::ConstructorInfo>> System::TypeInfo::GetConstructors(System::Reflection::BindingFlags bindingAttr) const
```

## TypeInfo::GetConstructors() const メソッド


現在の Type に定義されたすべての public コンストラクタを返します。

```cpp
ArrayPtr<SharedPtr<System::Reflection::ConstructorInfo>> System::TypeInfo::GetConstructors() const
```

## 参照

* 列挙型 [BindingFlags](../../../system.reflection/bindingflags/)
* 型定義 [ArrayPtr](../../arrayptr/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [ConstructorInfo](../../../system.reflection/constructorinfo/)
* クラス [TypeInfo](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)
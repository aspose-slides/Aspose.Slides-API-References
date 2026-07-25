---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_nullreferenceexception/is/
---
## 詳細_NullReferenceException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_NullReferenceException::Is(const System::TypeInfo &target) const override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 構造体は、現在のオブジェクトに対してテストする型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false。

## 備考

オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子に相当します。

## 参照

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_NullReferenceException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)
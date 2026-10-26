---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_applicationexception/is/
---
## Details_ApplicationException::Is(const System::TypeInfo\&) const メソッド

```cpp
bool System::Details_ApplicationException::Is(const System::TypeInfo &target) const override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 構造体で、現在のオブジェクトをテストする対象の型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false。

## 備考

対象の型（targetType）で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子に相当します。

## 参照

* Class [TypeInfo](../../typeinfo/)
* Class [Details_ApplicationException](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
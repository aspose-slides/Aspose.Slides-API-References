---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_invalidoperationexception/is/
---
## Details_InvalidOperationException::Is(const System::TypeInfo\&) const メソッド

```cpp
bool System::Details_InvalidOperationException::Is(const System::TypeInfo &target) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 構造体は、現在のオブジェクトに対してテストする型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false です。

## 備考

オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子に相当します。

## 関連項目

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_InvalidOperationException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: Is()
second_title: Aspose.Slides for C++ APIリファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_formatexception/is/
---
## Details_FormatException::Is(const System::TypeInfo\&) const メソッド

```cpp
bool System::Details_FormatException::Is(const System::TypeInfo &target) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 構造体は、現在のオブジェクトがテストされる型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false。

## 備考

オブジェクトが targetType で記述された型のインスタンスを表すかどうかを確認します。C# の 'is' 演算子の類似です。

## 参照

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_FormatException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_invalidcastexception/is/
---
## Details_InvalidCastException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_InvalidCastException::Is(const System::TypeInfo &target) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/)構造体で、現在のオブジェクトが比較される型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false。

## 備考

targetTypeで記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子の同等です。

## 参照

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_InvalidCastException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system/details_platformnotsupportedexception/is/
---
## Details_PlatformNotSupportedException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_PlatformNotSupportedException::Is(const System::TypeInfo &target) const override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) 構造体は、現在のオブジェクトに対してテストする型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は True、そうでない場合は false。

## 備考

オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。

## 参照

* クラス [TypeInfo](../../typeinfo/)
* クラス [Details_PlatformNotSupportedException](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)
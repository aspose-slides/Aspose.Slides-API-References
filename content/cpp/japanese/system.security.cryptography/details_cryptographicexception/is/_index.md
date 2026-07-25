---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.security.cryptography/details_cryptographicexception/is/
---
## Details_CryptographicException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Security::Cryptography::Details_CryptographicException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 構造体で、現在のオブジェクトに対してテストする型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false を返します。

## 備考

targetType が記述する型のインスタンスであるかどうかを確認します。C# の 'is' 演算子に相当します。

## 参照

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_CryptographicException](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)
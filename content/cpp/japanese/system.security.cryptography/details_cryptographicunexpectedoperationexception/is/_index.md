---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.security.cryptography/details_cryptographicunexpectedoperationexception/is/
---
## Details_CryptographicUnexpectedOperationException::Is(const System::TypeInfo\&) const メソッド




```cpp
bool System::Security::Cryptography::Details_CryptographicUnexpectedOperationException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) は、現在のオブジェクトがテスト対象とする型を記述する構造体です。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false。

## 備考

オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子に相当します。

## 参照

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_CryptographicUnexpectedOperationException](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.security.authentication/details_authenticationexception/is/
---
## Details_AuthenticationException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Security::Authentication::Details_AuthenticationException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 構造体は、現在のオブジェクトが比較される型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、それ以外の場合は false です。

## 備考

オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子の類似です。

## 参照

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_AuthenticationException](../)
* 名前空間 [System::Security::Authentication](../../)
* ライブラリ [Aspose.Slides](../../../)
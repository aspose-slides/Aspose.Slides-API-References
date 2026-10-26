---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 27
url: /ja/system.security/details_securityexception/is/
---
## Details_SecurityException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Security::Details_SecurityException::Is(const System::TypeInfo &target) const override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) 構造体は、現在のオブジェクトに対してテストする型を記述します。 |

### 戻り値

オブジェクトがタグ付けされた型またはそのサブクラスである場合は true、そうでない場合は false。

## 備考

targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子と同等です。

## 関連項目

* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [Details_SecurityException](../)
* 名前空間 [System::Security](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: ECCurve
second_title: Aspose.Slides for C++ API リファレンス
description: 楕円曲線です。
type: docs
weight: 716
url: /ja/system.security.cryptography/eccurve/
---
## ECCurve 構造体


楕円曲線です。

```cpp
class ECCurve
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | 指定された OID フレンドリ名から曲線を作成します。 |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | 指定された oid から曲線を作成します。 |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | 指定された OID 値から曲線を作成します。 |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | 名前付き曲線を表す [Oid](../oid/) を取得します。 |
| void [Validate](./validate/)() const | 現在の曲線を検証します。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [ECCurveType](./eccurvetype/) | 楕円曲線の種類。 |
## 参照

* 名前空間 [System::Security::Cryptography](../)
* ライブラリ [Aspose.Slides](../../)
---
title: ECCurve
second_title: Aspose.Slides for C++ API 參考
description: 一條橢圓曲線。
type: docs
weight: 716
url: /zh-hant/system.security.cryptography/eccurve/
---
## ECCurve 結構


一條橢圓曲線。

```cpp
class ECCurve
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | 從指定的 OID 友好名稱建立曲線。 |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | 從指定的 oid 建立曲線。 |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | 從指定的 OID 值建立曲線。 |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | 取得代表已命名曲線的 [Oid](../oid/)。 |
| void [Validate](./validate/)() const | 驗證目前的曲線。 |

## 列舉

| 列舉 | 說明 |
| --- | --- |
| [ECCurveType](./eccurvetype/) | 橢圓曲線的類型。 |

## 另請參閱

* 命名空間 [System::Security::Cryptography](../)
* 函式庫 [Aspose.Slides](../../)
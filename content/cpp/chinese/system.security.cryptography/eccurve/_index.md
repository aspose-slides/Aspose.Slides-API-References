---
title: ECCurve
second_title: Aspose.Slides for C++ API 参考
description: 椭圆曲线。
type: docs
weight: 716
url: /zh/system.security.cryptography/eccurve/
---
## ECCurve 结构体


椭圆曲线。

```cpp
class ECCurve
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | 从指定的 OID 友好名称创建曲线。 |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | 从指定的 oid 创建曲线。 |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | 从指定的 OID 值创建曲线。 |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | 获取表示已命名曲线的 [Oid](../oid/)。 |
| void [Validate](./validate/)() const | 验证当前曲线。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [ECCurveType](./eccurvetype/) | 椭圆曲线的类型。 |
## 参见

* 命名空间 [System::Security::Cryptography](../)
* 库 [Aspose.Slides](../../)
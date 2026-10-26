---
title: ECCurve
second_title: Aspose.Slides C++ API 레퍼런스
description: 타원 곡선.
type: docs
weight: 716
url: /ko/system.security.cryptography/eccurve/
---
## ECCurve 구조체

타원 곡선.

```cpp
class ECCurve
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | 지정된 OID 친숙한 이름에서 곡선을 생성합니다. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | 지정된 OID에서 곡선을 생성합니다. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | 지정된 OID 값에서 곡선을 생성합니다. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | 지정된 곡선을 나타내는 [Oid](../oid/)를 가져옵니다. |
| void [Validate](./validate/)() const | 현재 곡선을 검증합니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [ECCurveType](./eccurvetype/) | 타원 곡선의 유형. |
## 참고

* 네임스페이스 [System::Security::Cryptography](../)
* 라이브러리 [Aspose.Slides](../../)
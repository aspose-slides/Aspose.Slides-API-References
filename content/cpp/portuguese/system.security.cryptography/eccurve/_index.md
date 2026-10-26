---
title: ECCurve
second_title: Referência da API Aspose.Slides para C++
description: Uma curva elíptica.
type: docs
weight: 716
url: /pt/system.security.cryptography/eccurve/
---
## ECCurve struct

Uma curva elíptica.

```cpp
class ECCurve
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Cria uma curva a partir do nome amigável OID especificado. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Cria uma curva a partir do oid especificado. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Cria uma curva a partir do valor OID especificado. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Obtém [Oid](../oid/) representando a curva nomeada. |
| void [Validate](./validate/)() const | Valida a curva atual. |

## Enumerações

| Enum | Descrição |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Tipo de curva elíptica. |

## Ver Também

* Espaço de nomes [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)
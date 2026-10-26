---
title: ECCurve
second_title: Referencia de API de Aspose.Slides para C++
description: Una curva elíptica.
type: docs
weight: 716
url: /es/system.security.cryptography/eccurve/
---
## ECCurve estructura

Una curva elíptica.

```cpp
class ECCurve
```

## Métodos

| Method | Description |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Crear una curva a partir del nombre amigable OID especificado. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Crear una curva a partir del oid especificado. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Crear una curva a partir del valor OID especificado. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Obtiene [Oid](../oid/) que representa la curva con nombre. |
| void [Validate](./validate/)() const | Validar la curva actual. |

## Enumeraciones

| Enum | Description |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Tipo de curva elíptica. |

## Ver también

* Espacio de nombres [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)
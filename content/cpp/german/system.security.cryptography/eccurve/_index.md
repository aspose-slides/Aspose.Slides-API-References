---
title: ECCurve
second_title: Aspose.Slides für C++ API-Referenz
description: Eine elliptische Kurve.
type: docs
weight: 716
url: /de/system.security.cryptography/eccurve/
---
## ECCurve Struktur


Eine elliptische Kurve.

```cpp
class ECCurve
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Erstellt eine Kurve aus dem angegebenen OID-freundlichen Namen. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Erstellt eine Kurve aus der angegebenen OID. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Erstellt eine Kurve aus dem angegebenen OID-Wert. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Gibt [Oid](../oid/) zurück, das die benannte Kurve darstellt. |
| void [Validate](./validate/)() const | Validiert die aktuelle Kurve. |
## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Typ einer elliptischen Kurve. |
## Siehe auch

* Namensraum [System::Security::Cryptography](../)
* Bibliothek [Aspose.Slides](../../)
---
title: operator==()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of de huidige en de opgegeven TypeInfo-objecten gelijk zijn.
type: docs
weight: 443
url: /nl/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const method

Bepaalt of het huidige en het opgegeven [TypeInfo](../) objecten gelijk zijn.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Het [TypeInfo](../) object om mee te vergelijken |

### Return Value

True als de hashes van de objecten gelijk zijn, anders - false

## TypeInfo::operator==(std::nullptr_t) const method

Bepaalt of het huidige [TypeInfo](../) object een null-object is, d.w.z. geen type voorstelt.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### Return Value

True als het huidige [TypeInfo](../) object een null-object is, anders - false

## See Also

* Klasse [TypeInfo](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)
---
title: Is()
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 27
url: /de/system.runtime.serialization/details_serializationexception/is/
---
## Details_SerializationException::Is(const System::TypeInfo\&) const Methode




```cpp
bool System::Runtime::Serialization::Details_SerializationException::Is(const System::TypeInfo &target) const override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) Struktur, die den Typ beschreibt, gegen den das aktuelle Objekt getestet werden soll. |

### Rückgabewert

True, wenn das Objekt vom gekennzeichneten Typ oder dessen Unterklasse ist, andernfalls false.

## Hinweise

Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analogie zum C#-Operator 'is'.

## Siehe auch

* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [Details_SerializationException](../)
* Namensraum [System::Runtime::Serialization](../../)
* Bibliothek [Aspose.Slides](../../../)
---
title: FieldAttributes
second_title: Aspose.Slides für C++ API Referenz
description: Reflektierte Feldattribute.
type: docs
weight: 170
url: /de/system.reflection/fieldattributes/
---
## FieldAttributes Enum

Reflektierte Feldattribute.

```cpp
enum class FieldAttributes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| FieldAccessMask | 7 | Member-Zugriffsmaske. Verwenden Sie diese Maske, um Zugänglichkeitsinformationen abzurufen. |
| PrivateScope | 0 | Nicht referenzierbare Member. |
| Private | 1 | Private Member. |
| FamANDAssem | 2 | Private und Assembly-begrenzte Member. |
| Assembly | 3 | Assembly-begrenzte Member. |
| Family | 4 | Member, die vom Typ und Untertypen aus zugänglich sind. |
| FamORAssem | 5 | Member, die vom Typ, Untertypen und Assembly aus zugänglich sind. |
| Public | 6 | Member, die für jeden zugänglich sind. |
| Static | 16 | Statische Member als Gegenstück zu Instanz-Membern. |
| InitOnly | 32 | Konstante Member, die nur initialisiert, aber nicht geändert werden können. |
| Literal | 64 | Zur Kompilierzeit konstante Member. |
| NotSerialized | 128 | Nicht serialisierte Member. |
| SpecialName | 512 | Spezialfeld mit einem der untenstehenden Namen. |
| PinvokeImpl | 8192 | Interop-Weiterleitungsimplementierung. |
| ReservedMask | 38144 | Reservierte Flags ausschließlich für die Laufzeit. |
| RTSpecialName | 1024 | Runtime sollte die Namencodierung prüfen. |
| HasFieldMarshal | 4096 | Marshalling-Informationen liegen vor. |
| HasDefault | 32768 | Standardwert liegt vor. |
| HasFieldRVA | 256 | RVA liegt vor. |

## Siehe auch

* Namensraum [System::Reflection](../)
* Bibliothek [Aspose.Slides](../../)
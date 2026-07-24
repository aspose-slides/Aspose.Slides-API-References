---
title: SmartPtrInfo
second_title: Aspose.Slides für C++ API-Referenz
description: Dienstklasse zum Testen und Ändern des Inhalts von SmartPtr, ohne den endgültigen Typ zu kennen. Wird für Garbage Collection und die Erkennung von Schleifenreferenzen usw. verwendet. Betrachten Sie sie als einen 'pointer to pointer'. Wir können den Basistyp von SmartPtr nicht verwenden, da er keinen hat; stattdessen verwenden wir diese 'info' class.
type: docs
weight: 1249
url: /de/system/smartptrinfo/
---
## SmartPtrInfo Klasse

Dienstklasse zum Testen und Ändern des Inhalts von [SmartPtr](../smartptr/) ohne Kenntnis des endgültigen Typs. Wird für Garbage Collection und die Erkennung von Schleifenreferenzen usw. verwendet. Betrachten Sie sie als einen 'pointer to pointer'. Wir können den Basistyp von [SmartPtr](../smartptr/) nicht verwenden, da er keinen hat; stattdessen verwenden wir diese 'info' Klasse.

```cpp
class SmartPtrInfo
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Gibt das Roh-Objekt zurück, auf das der referenzierte Zeiger zeigt. |
| [Object](../object/) * [getObject](./getobject/)() const | Gibt das Objekt zurück, auf das der referenzierte Zeiger zeigt. |
| [Object](../object/) * [getOwned](./getowned/)() const | Gibt den vom Objekt besessenen Zeiger zurück. |
|  [operator bool](./operator_bool/)() const | Prüft, ob das Info-Objekt auf einen nicht-null Zeiger zeigt. |
| **bool** [operator!](./operator_not/)() const | Prüft, ob das Info-Objekt nicht auf einen nicht-null Zeiger zeigt. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Ermöglicht das Aufrufen von Methoden des [Object](../object/), auf das der referenzierte Zeiger zeigt. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Vergleicht die Werte der von zwei Info-Objekten referenzierten Zeiger mittels Less-Vergleich. |
|  [SmartPtrInfo](./smartptrinfo/)() | Erstellt ein leeres [SmartPtrInfo](./)-Objekt. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Erstellt ein [SmartPtrInfo](./)-Objekt mit Informationen zu einem bestimmten Smart-Pointer. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
---
title: MakeObject()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Objekt im Heap und gibt einen Shared-Pointer darauf zurück.
type: docs
weight: 2887
url: /de/system/makeobject/
---
## System::MakeObject(Args\&&...) Funktion

Erstellt ein Objekt im Heap und gibt einen Shared-Pointer darauf zurück.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Klasse, die instanziiert werden soll. |
| Args | Typen der Konstruktorargumente. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | Args\&&... | Konstruktorargumente. |

### Rückgabewert

[SmartPtr](../smartptr/) zu dem neu erstellten Objekt, immer im Shared-Modus.

## System::MakeObject(Args\&&...) Funktion

Erstellt ein Objekt im Heap und gibt einen Shared-Pointer darauf zurück.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [SmartPtr](../smartptr/) zur Klasse, die zu instanziieren ist. |
| Args | Typen der Konstruktorargumente. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | Args\&&... | Konstruktorargumente. |

### Rückgabewert

[SmartPtr](../smartptr/) zu dem neu erstellten Objekt, immer im Shared-Modus.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Struktur [IsSmartPtr](../issmartptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
---
title: MakeSharedPtr()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert rohen Zeiger in einen Smart-Pointer.
type: docs
weight: 2900
url: /de/system/makesharedptr/
---
## System::MakeSharedPtr(X *) Funktion


Konvertiert rohen Zeiger in einen Smart-Pointer.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| X | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | X * | Rohzeiger auf Objekt. |

### Rückgabewert

Gemeinsamer Smart-Pointer auf Objekt.

## System::MakeSharedPtr(const X *) Funktion


Konvertiert rohen Zeiger in einen Smart-Pointer. Überladung für const-Zeiger. Nützlich z. B. beim Verwenden der 'this'-Variablen in C#-Methoden, die als const übersetzt werden.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| X | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | const X * | Rohzeiger auf Objekt. |

### Rückgabewert

Gemeinsamer Smart-Pointer auf Objekt.

## Siehe auch

* Klasse [SmartPtr](../smartptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
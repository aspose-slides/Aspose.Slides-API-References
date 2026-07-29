---
title: MakeSharedPtr()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar råpekare till smart pekare.
type: docs
weight: 2900
url: /sv/system/makesharedptr/
---
## System::MakeSharedPtr(X *) funktion

Konverterar råpekare till smart pekare.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| X | Pointee-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | X * | Råpekare till objektet. |

### Returvärde

Delad smart pekare till objektet.

## System::MakeSharedPtr(const X *) funktion

Konverterar råpekare till smart pekare. Överlagring för const-pekare. Användbar t.ex. när man använder variabeln 'this' i C#-metoder som översätts som const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| X | Pointee-typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | const X * | Råpekare till objektet. |

### Returvärde

Delad smart pekare till objektet.

## Se även

* Klass [SmartPtr](../smartptr/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)
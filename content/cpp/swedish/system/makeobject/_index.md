---
title: MakeObject()
second_title: Aspose.Slides för C++ API-referens
description: Skapar objekt på heapen och returnerar en delad pekare till det.
type: docs
weight: 2887
url: /sv/system/makeobject/
---
## System::MakeObject(Args\&&...) funktion


Skapar ett objekt på heapen och returnerar en delad pekare till det.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Klass att instansiera. |
| Args | Konstruktörsargumentens typer. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | Args\&&... | Konstruktörsargument. |

### Returvärde

[SmartPtr](../smartptr/) till det nyss skapade objektet, alltid i delat läge.

## System::MakeObject(Args\&&...) funktion


Skapar ett objekt på heapen och returnerar en delad pekare till det.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [SmartPtr](../smartptr/) till klass att instansiera. |
| Args | Konstruktörsargumentens typer. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | Args\&&... | Konstruktörsargument. |

### Returvärde

[SmartPtr](../smartptr/) till det nyss skapade objektet, alltid i delat läge.

## Se även

* Klass [SmartPtr](../smartptr/)
* Struktur [IsSmartPtr](../issmartptr/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)
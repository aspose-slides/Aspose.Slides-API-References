---
title: MakeObject()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří objekt na haldě a vrátí na něj sdílený ukazatel.
type: docs
weight: 2887
url: /cs/system/makeobject/
---
## System::MakeObject(Args\&&...) funkce

Vytvoří objekt na haldě a vrátí na něj sdílený ukazatel.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Třída k vytvoření. |
| Args | Typy argumentů konstruktoru. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| args | Args\&&... | Argumenty konstruktoru. |

### Návratová hodnota

[SmartPtr](../smartptr/) na nově vytvořený objekt, vždy v sdíleném režimu.

## System::MakeObject(Args\&&...) funkce

Vytvoří objekt na haldě a vrátí na něj sdílený ukazatel.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [SmartPtr](../smartptr/) k třídě, která se má vytvořit. |
| Args | Typy argumentů konstruktoru. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| args | Args\&&... | Argumenty konstruktoru. |

### Návratová hodnota

[SmartPtr](../smartptr/) na nově vytvořený objekt, vždy v sdíleném režimu.

## See Also

* Třída [SmartPtr](../smartptr/)
* Struktura [IsSmartPtr](../issmartptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)
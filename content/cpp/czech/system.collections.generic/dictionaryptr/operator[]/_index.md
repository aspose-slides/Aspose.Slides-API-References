---
title: operator[]()
second_title: Aspose.Slides pro C++ API Reference
description: Přístupový operátor pro práci s konverzí typu klíče.
type: docs
weight: 14
url: /cs/system.collections.generic/dictionaryptr/operator[]/
---
## DictionaryPtr::operator[](const X\&) const metoda

Přístupový operátor pro práci s konverzí typu klíče.

```cpp
template<class X> V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const X &key) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| X | Zdrojový typ klíče. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key | const X\& | [Dictionary](../../dictionary/) klíč. |

### Návratová hodnota

Reference na hodnotu odpovídající předanému klíči, existující nebo nově vytvořenou.

## DictionaryPtr::operator[](const T\&) const metoda

Přístupový operátor.

```cpp
V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const T &key) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key | const T\& | [Dictionary](../../dictionary/) klíč. |

### Návratová hodnota

Reference na hodnotu odpovídající předanému klíči, existující nebo nově vytvořenou.

## Viz také

* Třída [DictionaryPtr](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)
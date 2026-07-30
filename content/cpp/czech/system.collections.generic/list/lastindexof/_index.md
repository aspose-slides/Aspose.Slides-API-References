---
title: LastIndexOf()
second_title: Aspose.Slides pro C++ API Reference
description: Vyhledá zadaný objekt a vrátí nulový index posledního výskytu v celém seznamu.
type: docs
weight: 469
url: /cs/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const metoda


Vyhledá zadaný objekt a vrátí nulový index posledního výskytu v celém seznamu.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | const T\& | Objekt, který se má najít v seznamu |

### Návratová hodnota

Nulový index posledního výskytu položky v celém [List](../), pokud je nalezen; jinak, -1.

## List::LastIndexOf(const T\&, int32_t) const metoda


Vyhledá zadaný objekt a vrátí nulový index posledního výskytu v rozsahu prvků v [List](../), který se rozšiřuje od prvního prvku po zadaný index.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | const T\& | Objekt, který se má najít v seznamu |
| index | **int32_t** | Nulový počáteční index zpětného vyhledávání. |

### Návratová hodnota

Nulový index posledního výskytu položky v rozsahu prvků v [List](../), který se rozšiřuje od prvního prvku po index, pokud je nalezen; jinak, -1.

## List::LastIndexOf(const T\&, int32_t, int32_t) const metoda


Vyhledá zadaný objekt a vrátí nulový index posledního výskytu v rozsahu prvků v [List](../), který obsahuje zadaný počet prvků a končí ve zadaném indexu.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | const T\& | Objekt, který se má najít v [List](../) |
| index | **int32_t** | Nulový počáteční index zpětného vyhledávání. |
| count | **int32_t** | Počet prvků v sekci, která se má prohledat. |

### Návratová hodnota

Nulový index posledního výskytu položky v rozsahu prvků v [List](../), který obsahuje počet prvků count a končí v indexu, pokud je nalezen; jinak, -1.

## Viz také

* Třída [List](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)
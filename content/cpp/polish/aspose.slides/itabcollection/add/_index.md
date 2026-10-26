---
title: Add()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Dodaje tabulator do kolekcji.
type: docs
weight: 14
url: /pl/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) metoda

Dodaje [Tab](../../tab/) do kolekcji.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) position. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) alignment. |

### Wartość zwracana

Dodany tabulator.

## ITabCollection::Add(System::SharedPtr\<ITab\>) metoda

Dodaje [Tab](../../tab/) do kolekcji.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Obiekt [Tab](../../tab/) do dodania na końcu kolekcji. |

### Wartość zwracana

Indeks, pod którym dodano tabulator.

## Zobacz także

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
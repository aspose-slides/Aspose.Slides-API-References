---
title: Add()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá Tab do kolekce.
type: docs
weight: 14
url: /cs/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) metoda

Přidá [Tab](../../tab/) do kolekce.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) pozice. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) zarovnání. |

### Návratová hodnota

Přidaný tabulátor.

## ITabCollection::Add(System::SharedPtr\<ITab\>) metoda

Přidá [Tab](../../tab/) do kolekce.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Objekt [Tab](../../tab/), který má být přidán na konec kolekce. |

### Návratová hodnota

Index, ve kterém byl tabulátor přidán.

## Viz také

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [ITab](../../itab/)
* třída [ITabCollection](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)
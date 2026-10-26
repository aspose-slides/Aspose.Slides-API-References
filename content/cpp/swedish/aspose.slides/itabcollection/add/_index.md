---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en flik i samlingen.
type: docs
weight: 14
url: /sv/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) metod

Lägger till en [Tab](../../tab/) i samlingen.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) position. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) justering. |

### Returvärde

Tillagd flik.

## ITabCollection::Add(System::SharedPtr\<ITab\>) metod

Lägger till en [Tab](../../tab/) i samlingen.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Objektet [Tab](../../tab/) som ska läggas till i slutet av samlingen. |

### Returvärde

Indexet där fliken lades till.

## Se också

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ITab](../../itab/)
* Klass [ITabCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
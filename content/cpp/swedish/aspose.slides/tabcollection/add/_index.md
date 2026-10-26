---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en Tab i samlingen.
type: docs
weight: 53
url: /sv/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) metod


Lägger till en [Tab](../../tab/) i samlingen.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```


### Returvärde

Tillagd flik.

## TabCollection::Add(System::SharedPtr\<ITab\>) metod


Lägger till en [Tab](../../tab/) i samlingen.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | Objektet [Tab](../../tab/) som ska läggas till i slutet av samlingen. |

### Returvärde

Indexet där fliken lades till.

## Se även

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [TabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: Add()
second_title: Aspose.Slides για την αναφορά API του C++
description: Προσθέτει ένα Tab στη συλλογή.
type: docs
weight: 14
url: /el/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) μέθοδος

Προσθέτει ένα [Tab](../../tab/) στην συλλογή.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) position. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) alignment. |

### Τιμή επιστροφής

Προστέθηκε στήλη.

## ITabCollection::Add(System::SharedPtr\<ITab\>) μέθοδος

Προσθέτει ένα [Tab](../../tab/) στην συλλογή.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | The [Tab](../../tab/) object to be added at the end of the collection. |

### Τιμή επιστροφής

Ο δείκτης στον οποίο προστέθηκε η στήλη.

## Δείτε επίσης

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
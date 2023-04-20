---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds a Tab to the collection.
type: docs
weight: 14
url: /cpp/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) method


Adds a [Tab](../../tab/) to the collection.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) position. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) alignment. |

### Return Value

Added tab.

## ITabCollection::Add(System::SharedPtr\<ITab\>) method


Adds a [Tab](../../tab/) to the collection.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | The [Tab](../../tab/) object to be added at the end of the collection. |

### Return Value

The index at which the tab was added.

## See Also

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITab](../../itab/)
* Class [ITabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds a Tab to the collection.
type: docs
weight: 53
url: /aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) method


Adds a [Tab](../../tab/) to the collection.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```


### Return Value

Added tab.

## TabCollection::Add(System::SharedPtr\<ITab\>) method


Adds a [Tab](../../tab/) to the collection.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
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
* Class [TabCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
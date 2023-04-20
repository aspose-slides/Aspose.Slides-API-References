---
title: Equals()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether the specified region is identical to the region represented by the current object on the specified drawing surface.
type: docs
weight: 157
url: /cpp/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) method


Determines whether the specified region is identical to the region represented by the current object on the specified drawing surface.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | The region to compare this region with |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | A drawing surface |

### Return Value

True if the interior of the specified region is identical to the interior of the region represented by the current objcet when the transformation associated with the **g** parameter is applied; otherwise - false

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
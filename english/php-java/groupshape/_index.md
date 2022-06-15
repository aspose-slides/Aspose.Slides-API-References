---
title: GroupShape
type: docs
weight: 0
url: /php-java/groupshape/
---

# GroupShape class

  Represents a group of shapes on a slide.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getGroupShapeLock](/php-java/groupshape/getgroupshapelock/)() | IGroupShapeLock | Returns shape's locks. Read-only IGroupShapeLock. |
| [getLineFormat](/php-java/groupshape/getlineformat/)() | ILineFormat | Returns the LineFormat object that contains line formatting properties for a shape. Note: Returns null for GroupShape objects because they don't have line properties. Read-only ILineFormat. |
| [getShapes](/php-java/groupshape/getshapes/)() | IShapeCollection | Returns the collection of shapes inside the group. Read-only IShapeCollection. |

---
title: get_EndShapeConnectedTo()
second_title: Aspose.Slides for C++ API Reference
description: Returns the shape to attach the end of the connector to. Read IShape.
type: docs
weight: 66
url: /aspose.slides/connector/get_endshapeconnectedto/
---
## Connector::get_EndShapeConnectedTo() method


Returns the shape to attach the end of the connector to. Read [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Connector::get_EndShapeConnectedTo() override
```


### Exceptions

| Exception | Description |
| --- | --- |
| [System::ArgumentException](../../../system/argumentexception/) | Thrown when connected shape doesn't has any connection sites ([IShape::get_ConnectionSiteCount](../../ishape/get_connectionsitecount/) equals zero) |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [Connector](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
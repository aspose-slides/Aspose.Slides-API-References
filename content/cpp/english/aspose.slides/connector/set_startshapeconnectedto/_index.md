---
title: set_StartShapeConnectedTo()
second_title: Aspose.Slides for C++ API Reference
description: Sets the shape to attach the beginning of the connector to. Write IShape.
type: docs
weight: 53
url: /aspose.slides/connector/set_startshapeconnectedto/
---
## Connector::set_StartShapeConnectedTo(System::SharedPtr\<IShape\>) method


Sets the shape to attach the beginning of the connector to. Write [IShape](../../ishape/).

```cpp
void Aspose::Slides::Connector::set_StartShapeConnectedTo(System::SharedPtr<IShape> value) override
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
---
title: set_EndShapeConnectedTo()
second_title: Aspose.Slides for C++ API Reference
description: Sets the shape to attach the end of the connector to. Write IShape.
type: docs
weight: 53
url: /aspose.slides/iconnector/set_endshapeconnectedto/
---
## IConnector::set_EndShapeConnectedTo(System::SharedPtr\<IShape\>) method


Sets the shape to attach the end of the connector to. Write [IShape](../../ishape/).

```cpp
virtual void Aspose::Slides::IConnector::set_EndShapeConnectedTo(System::SharedPtr<IShape> value)=0
```


### Exceptions

| Exception | Description |
| --- | --- |
| [System::ArgumentException](../../../system/argumentexception/) | Thrown when connected shape doesn't has any connection sites ([IShape::get_ConnectionSiteCount](../../ishape/get_connectionsitecount/) equals zero) |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IConnector](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
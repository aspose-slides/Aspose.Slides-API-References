---
title: get_EndShapeConnectedTo()
second_title: Aspose.Slides for C++ API Reference
description: Returns the shape to attach the end of the connector to. Read IShape.
type: docs
weight: 40
url: /aspose.slides/iconnector/get_endshapeconnectedto/
---
## IConnector::get_EndShapeConnectedTo() method


Returns the shape to attach the end of the connector to. Read [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IConnector::get_EndShapeConnectedTo()=0
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
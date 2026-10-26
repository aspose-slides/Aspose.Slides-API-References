---
title: GetGeometryPaths()
second_title: Aspose.Slides for C++ API संदर्भ
description: ज्योमिति आकार के पाथ की प्रति लौटाता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होते हैं।
type: docs
weight: 53
url: /hi/aspose.slides/igeometryshape/getgeometrypaths/
---
## IGeometryShape::GetGeometryPaths() विधि


ज्योमिति आकार के पाथ की प्रति लौटाता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होते हैं।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::IGeometryShape::GetGeometryPaths()=0
```


### प्रतिफल मान

ऐरे का [IGeometryPath](../../igeometrypath/)
## टिप्पणियाँ



उदाहरण: 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();

auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath = shape->GetGeometryPaths()->idx_get(0);

geometryPath->LineTo(100.0f, 50.0f, 1);
geometryPath->LineTo(100.0f, 50.0f, 4);

shape->SetGeometryPath(geometryPath);

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* वर्ग [IGeometryPath](../../igeometrypath/)
* वर्ग [IGeometryShape](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
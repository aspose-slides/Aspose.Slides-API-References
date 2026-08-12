---
title: SetGeometryPaths()
second_title: Aspose.Slides for C++ API संदर्भ
description: "शेप जियोमेट्री को IGeometryPath की एरे से अपडेट करता है। कॉर्डिनेट्स शेप के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। शेप के प्रकार (ShapeType) को ShapeType::Custom में बदलता है।"
type: docs
weight: 79
url: /hi/aspose.slides/igeometryshape/setgeometrypaths/
---
## IGeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) method

शेप जियोमेट्री को [IGeometryPath](../../igeometrypath/) की एरे से अपडेट करता है। कॉर्डिनेट्स शेप के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([ShapeType](../../shapetype/)) को [ShapeType::Custom](../../shapetype/) में बदलता है।

```cpp
virtual void Aspose::Slides::IGeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths)=0
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | एरे जियोमेट्री पाथ्स |

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

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IGeometryPath](../../igeometrypath/)
* क्लास [IGeometryShape](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
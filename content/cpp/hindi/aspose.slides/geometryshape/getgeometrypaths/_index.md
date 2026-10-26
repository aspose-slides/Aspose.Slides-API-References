---
title: GetGeometryPaths()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ज्यामितीय आकार के पथ की प्रतिलिपि लौटाता है। निर्देशांक आकार के बाएँ ऊपर कोने के सापेक्ष होते हैं।
type: docs
weight: 53
url: /hi/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() मेथड


ज्यामितीय आकार के पथ की प्रतिलिपि लौटाता है। निर्देशांक आकार के बाएं ऊपर कोने के सापेक्ष होते हैं।

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```


### रिटर्न वैल्यू

Array of [IGeometryPath](../../igeometrypath/)
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
* क्लास [IGeometryPath](../../igeometrypath/)
* क्लास [GeometryShape](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
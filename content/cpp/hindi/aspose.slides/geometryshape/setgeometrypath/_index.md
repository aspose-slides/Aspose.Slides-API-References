---
title: SetGeometryPath()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "IGeometryPath ऑब्जेक्ट से आकार ज्यामिति को अद्यतन करता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। आकार का प्रकार (ShapeType) को ShapeType::Custom में बदलता है।"
type: docs
weight: 66
url: /hi/aspose.slides/geometryshape/setgeometrypath/
---
## GeometryShape::SetGeometryPath(System::SharedPtr\<IGeometryPath\>) विधि

[IGeometryPath](../../igeometrypath/) ऑब्जेक्ट से आकार ज्यामिति को अद्यतन करता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। आकार का प्रकार ([ShapeType](../../shapetype/)) को [ShapeType::Custom](../../shapetype/) में बदलता है।

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPath(System::SharedPtr<IGeometryPath> geometryPath) override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\> | ज्यामिति पथ |
## टिप्पणियाँ



उदाहरण: 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();

auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath0 = MakeObject<GeometryPath>();
geometryPath0->MoveTo(0.0f, 0.0f);
geometryPath0->LineTo(shape->get_Width(), 0.0f);
geometryPath0->LineTo(shape->get_Width(), shape->get_Height() / 3);
geometryPath0->LineTo(0.0f, shape->get_Height() / 3);
geometryPath0->CloseFigure();

auto geometryPath1 = MakeObject<GeometryPath>();
geometryPath1->MoveTo(0.0f, shape->get_Height() / 3 * 2);
geometryPath1->LineTo(shape->get_Width(), shape->get_Height() / 3 * 2);
geometryPath1->LineTo(shape->get_Width(), shape->get_Height());
geometryPath1->LineTo(0.0f, shape->get_Height());
geometryPath1->CloseFigure();

shape->SetGeometryPaths(StaticCastArray<SharedPtr<IGeometryPath>>(MakeArray<SharedPtr<GeometryPath>>({geometryPath0, geometryPath1})));

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IGeometryPath](../../igeometrypath/)
* क्लास [GeometryShape](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
---
title: SetGeometryPaths()
second_title: Aspose.Slides C++ के लिए एपीआई संदर्भ
description: "IGeometryPath की array से आकृति की geometry को अपडेट करता है। निर्देशांक आकृति के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। आकृति (ShapeType) का प्रकार ShapeType::Custom में बदल देता है।"
type: docs
weight: 79
url: /hi/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) मेथड


[IGeometryPath](../../igeometrypath/) की array से shape geometry को अपडेट करता है। निर्देशांक shape के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। shape ([ShapeType](../../shapetype/)) का प्रकार [ShapeType::Custom](../../shapetype/) में बदल देता है।

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | ऐरे ज्योमेट्री पाथ |
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

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IGeometryPath](../../igeometrypath/)
* क्लास [GeometryShape](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
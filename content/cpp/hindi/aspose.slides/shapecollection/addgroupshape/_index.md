---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया खाली समूह आकार बनाता है और उसे आकार संग्रह के अंत में जोड़ता है। समूह का फ्रेम स्वचालित रूप से किसी भी जोड़े गए आकारों के अनुसार समायोजित हो जाएगा।
type: docs
weight: 391
url: /hi/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() विधि

एक नया खाली समूह आकार बनाता है और उसे आकार संग्रह के अंत में जोड़ता है। समूह का फ्रेम स्वचालित रूप से किसी भी जोड़े गए आकारों के अनुसार समायोजित हो जाएगा।

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### वापसी मान

नया निर्मित [IGroupShape](../../igroupshape/)।

## टिप्पणी

निम्न उदाहरण दिखाता है कि कैसे PowerPoint [Presentation](../../presentation/) की स्लाइड में एक समूह आकार जोड़ा जाए।
```cpp
// Presentation क्लास का उदाहरण बनाएं
auto pres = System::MakeObject<Presentation>();

// पहली स्लाइड प्राप्त करें
auto slide = pres->get_Slides()->idx_get(0);
// स्लाइडों के shape संग्रह तक पहुँच रहे हैं
auto slideShapes = slide->get_Shapes();
// स्लाइड में समूह आकार जोड़ रहे हैं
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// जोड़े गए समूह आकार के भीतर आकार जोड़ना
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// समूह आकार फ्रेम जोड़ रहे हैं
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// PPTX फ़ाइल को डिस्क पर लिखें
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) विधि

एक नया समूह आकार बनाता है, निर्दिष्ट SVG चित्र को व्यक्तिगत आकारों में बदलता है, और परिणामी समूह को आकार संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) जिसमें वेक्टर सामग्री है जिसे आकारों में परिवर्तित किया जाएगा। |
| x | **float** | समूह के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | समूह के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | समूह के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | समूह के फ्रेम की ऊँचाई, पॉइंट्स में। |

### वापसी मान

नया निर्मित [IGroupShape](../../igroupshape/)।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IGroupShape](../../igroupshape/)
* क्लास [ShapeCollection](../)
* क्लास [ISvgImage](../../isvgimage/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
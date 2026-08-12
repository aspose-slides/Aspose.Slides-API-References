---
title: GetBasePlaceholder()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक बुनियादी placeholder shape लौटाता है (लेआउट और/या मास्टर स्लाइड से shape जिसे वर्तमान shape ने विरासत में प्राप्त किया है)।
type: docs
weight: 573
url: /hi/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() विधि

वर्तमान shape से विरासत में प्राप्त लेआउट और/या master स्लाइड से एक बुनियादी placeholder shape लौटाता है।

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## टिप्पणियाँ

यदि वर्तमान shape विरासत में नहीं मिला है तो null लौटाया जाता है।

```cpp
// प्लेसहोल्डर shape के सभी (मास्टर/लेआउट/स्लाइड) एनिमेटेड इफ़ेक्ट प्राप्त करें
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IShape](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
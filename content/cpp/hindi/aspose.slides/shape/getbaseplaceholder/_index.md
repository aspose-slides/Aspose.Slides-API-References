---
title: GetBasePlaceholder()
second_title: Aspose.Slides C++ के लिये API संदर्भ
description: एक मूल placeholder shape लौटाता है (लेआउट और/या मास्टर स्लाइड से वह shape, जिससे वर्तमान shape विरासत में मिला है)।
type: docs
weight: 638
url: /hi/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() मेथड

वर्तमान shape से विरासत में मिली लेआउट और/या मास्टर स्लाइड से मूल placeholder shape लौटाता है।

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## टिप्पणियाँ

यदि वर्तमान shape विरासत में नहीं मिली है तो null लौटाया जाता है।

```cpp
// placeholder shape के सभी (master/layout/slide) एनीमेटेड प्रभाव प्राप्त करें
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IShape](../../ishape/)
* क्लास [Shape](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)
---
title: AlignShapes()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड पर सभी आकारों की स्थितियों को बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें एक-दूसरे के सापेक्ष संरेखित करता है।
type: docs
weight: 27
url: /hi/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) मेथड


स्लाइड पर सभी आकारों की स्थितियों को बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें एक-दूसरे के सापेक्ष संरेखित करता है।

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | निर्धारित करता है कि कौन-सा संरेखण प्रकार लागू किया जाएगा। |
| alignToSlide | **bool** | यदि true हो, तो आकार स्लाइड किनारों के सापेक्ष संरेखित किए जाएंगे। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | पैरेंट स्लाइड। |
## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) मेथड


स्लाइड पर चयनित आकारों की स्थितियों को बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें एक-दूसरे के सापेक्ष संरेखित करता है।

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | निर्धारित करता है कि कौन-सा संरेखण प्रकार लागू किया जाएगा। |
| alignToSlide | **bool** | यदि true हो, तो आकार स्लाइड किनारों के सापेक्ष संरेखित किए जाएंगे। |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | पैरेंट स्लाइड। |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | संरेखित किए जाने वाले आकारों के सूचकांक। |
## टिप्पणी



उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto slide = pres->get_Slides()->idx_get(0);
auto shape1 = slide->get_Shapes()->idx_get(0);
auto shape2 = slide->get_Shapes()->idx_get(1);
SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, false, pres->get_Slides()->idx_get(0),
    System::MakeArray<int32_t>({
        slide->get_Shapes()->IndexOf(shape1),
        slide->get_Shapes()->IndexOf(shape2)
    }));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) मेथड


समूह आकार के भीतर सभी आकारों की स्थितियों को बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें एक-दूसरे के सापेक्ष संरेखित करता है।

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | निर्धारित करता है कि कौन-सा संरेखण प्रकार लागू किया जाएगा। |
| alignToSlide | **bool** | यदि true हो, तो आकार स्लाइड किनारों के सापेक्ष संरेखित किए जाएंगे। |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | पैरेंट समूह आकार। |
## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) मेथड


समूह आकार के भीतर चयनित आकारों की स्थितियों को बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें एक-दूसरे के सापेक्ष संरेखित करता है।

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | निर्धारित करता है कि कौन-सा संरेखण प्रकार लागू किया जाएगा। |
| alignToSlide | **bool** | यदि true हो, तो आकार स्लाइड किनारों के सापेक्ष संरेखित किए जाएंगे। |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | पैरेंट समूह आकार। |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | संरेखित किए जाने वाले आकारों के सूचकांक। |
## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## देखें

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [SlideUtil](../)
* Class [IGroupShape](../../../aspose.slides/igroupshape/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)
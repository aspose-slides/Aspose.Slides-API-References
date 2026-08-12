---
title: SlideUtil
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: प्रस्तुति में आकार और पाठ को खोजने में मदद करने वाले मेथड्स प्रदान करता है।
type: docs
weight: 14
url: /hi/aspose.slides.util/slideutil/
---
## SlideUtil क्लास

प्रस्तुति में आकार और टेक्स्ट को खोजने में मदद करने वाले मेथड्स प्रदान करता है।

```cpp
class SlideUtil
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | स्लाइड में सभी आकारों की व्यवस्था बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या एक-दूसरे के सापेक्ष संरेखित करता है। |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | स्लाइड में सभी आकारों की व्यवस्था बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या एक-दूसरे के सापेक्ष संरेखित करता है। |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | स्लाइड में सभी आकारों की व्यवस्था बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या एक-दूसरे के सापेक्ष संरेखित करता है। |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | स्लाइड में सभी आकारों की व्यवस्था बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या एक-दूसरे के सापेक्ष संरेखित करता है। |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | प्रस्तुति में दिया गया स्वरूप के साथ टेक्स्ट को खोजता और प्रतिस्थापित करता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | PPTX प्रस्तुति में वैकल्पिक टेक्स्ट द्वारा आकार खोजता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | PPTX प्रस्तुति में स्लाइड पर वैकल्पिक टेक्स्ट द्वारा आकार खोजता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | निर्दिष्ट स्लाइड पर सभी आकारों को खोजता है जो दिए गए प्लेसहोल्डर प्रकार के मिलते हैं। |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | PPTX प्रस्तुति में स्लाइड पर सभी टेक्स्ट फ्रेम लौटाता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | PPTX प्रस्तुति में सभी टेक्स्ट फ्रेम लौटाता है। |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | निर्दिष्ट स्लाइड पर सभी टेक्स्ट फ्रेम लौटाता है जिनमें दिया गया टेक्स्ट है। |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | एक स्रोत फ़ाइल स्वरूप को संबंधित [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) में परिवर्तित करता है। |
## देखें

* नेमस्पेस [Aspose::Slides::Util](../)
* लाइब्रेरी [Aspose.Slides](../../)
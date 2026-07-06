---
title: AlignShapes
second_title: Aspose.Sildes for .NET API संदर्भ
description: स्लाइड पर सभी आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें आपस में सापेक्ष रूप से संरेखित करता है।
type: docs
weight: 10
url: /hi/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

स्लाइड पर सभी आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें आपस में सापेक्ष रूप से संरेखित करता है।

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | निर्धारित करता है कि किस प्रकार का संरेखण लागू किया जाएगा। |
| alignToSlide | Boolean | यदि true है, तो आकार स्लाइड के किनारों के सापेक्ष संरेखित किए जाएंगे। |
| slide | IBaseSlide | पैरेंट स्लाइड। |

### उदाहरण

उदाहरण:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### संबंधित देखें

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

स्लाइड पर चयनित आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें आपस में सापेक्ष रूप से संरेखित करता है।

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | निर्धारित करता है कि किस प्रकार का संरेखण लागू किया जाएगा। |
| alignToSlide | Boolean | यदि true है, तो आकार स्लाइड के किनारों के सापेक्ष संरेखित किए जाएंगे। |
| slide | IBaseSlide | पैरेंट स्लाइड। |
| shapeIndexes | Int32[] | संरेखित किए जाने वाले आकारों के इंडेक्स। |

### उदाहरण

उदाहरण:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   ISlide slide = pres.Slides[0];
   IShape shape1 = slide.Shapes[0];
   IShape shape2 = slide.Shapes[1]; 

   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, false, pres.Slides[0], new int[]
   {
      slide.Shapes.IndexOf(shape1),
      slide.Shapes.IndexOf(shape2)
   });
}
```

### संबंधित देखें

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

समूह आकार के भीतर सभी आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें आपस में सापेक्ष रूप से संरेखित करता है।

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | निर्धारित करता है कि किस प्रकार का संरेखण लागू किया जाएगा। |
| alignToSlide | Boolean | यदि true है, तो आकार स्लाइड के किनारों के सापेक्ष संरेखित किए जाएंगे। |
| groupShape | IGroupShape | पैरेंट समूह आकार। |

### उदाहरण

उदाहरण:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### संबंधित देखें

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

समूह आकार के भीतर चयनित आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या उन्हें आपस में सापेक्ष रूप से संरेखित करता है।

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | निर्धारित करता है कि किस प्रकार का संरेखण लागू किया जाएगा। |
| alignToSlide | Boolean | यदि true है, तो आकार स्लाइड के किनारों के सापेक्ष संरेखित किए जाएंगे। |
| groupShape | IGroupShape | पैरेंट समूह आकार। |
| shapeIndexes | Int32[] | संरेखित किए जाने वाले आकारों के इंडेक्स। |

### उदाहरण

उदाहरण:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### संबंधित देखें

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
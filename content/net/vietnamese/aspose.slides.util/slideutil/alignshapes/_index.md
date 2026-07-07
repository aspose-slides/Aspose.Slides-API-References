---
title: AlignShapes
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Thay đổi vị trí của tất cả các hình dạng trên slide. Căn các hình dạng vào lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.
type: docs
weight: 10
url: /vi/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Thay đổi vị trí của tất cả các hình dạng trên slide. Căn các hình dạng vào lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | IBaseSlide | Parent slide. |

### Ví dụ

Ví dụ:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Xem thêm

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* giao diện [IBaseSlide](../../../aspose.slides/ibaseslide)
* lớp [SlideUtil](../../slideutil)
* không gian tên [Aspose.Slides.Util](../../slideutil)
* tập hợp [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Thay đổi vị trí của các hình dạng đã chọn trên slide. Căn các hình dạng vào lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | IBaseSlide | Parent slide. |
| shapeIndexes | Int32[] | Indexes of shapes to be aligned. |

### Ví dụ

Ví dụ:

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

### Xem thêm

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* giao diện [IBaseSlide](../../../aspose.slides/ibaseslide)
* lớp [SlideUtil](../../slideutil)
* không gian tên [Aspose.Slides.Util](../../slideutil)
* tập hợp [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Thay đổi vị trí của tất cả các hình dạng bên trong hình dạng nhóm. Căn các hình dạng vào lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | IGroupShape | Parent group shape. |

### Ví dụ

Ví dụ:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Xem thêm

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* giao diện [IGroupShape](../../../aspose.slides/igroupshape)
* lớp [SlideUtil](../../slideutil)
* không gian tên [Aspose.Slides.Util](../../slideutil)
* tập hợp [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Thay đổi vị trí của các hình dạng đã chọn bên trong hình dạng nhóm. Căn các hình dạng vào lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | IGroupShape | Parent group shape. |
| shapeIndexes | Int32[] | Indexes of shapes to be aligned. |

### Ví dụ

Ví dụ:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Xem thêm

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* giao diện [IGroupShape](../../../aspose.slides/igroupshape)
* lớp [SlideUtil](../../slideutil)
* không gian tên [Aspose.Slides.Util](../../slideutil)
* tập hợp [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
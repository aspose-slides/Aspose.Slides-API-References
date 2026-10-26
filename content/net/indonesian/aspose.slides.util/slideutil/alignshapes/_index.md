---
title: AlignShapes
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mengubah penempatan semua bentuk pada slide. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya secara relatif satu sama lain.
type: docs
weight: 10
url: /id/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Mengubah penempatan semua bentuk pada slide. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya secara relatif satu sama lain.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Menentukan jenis penyelarasan yang akan diterapkan. |
| alignToSlide | Boolean | Jika true, shape akan diselaraskan relatif terhadap tepi slide. |
| slide | IBaseSlide | Slide induk. |

### Contoh

Contoh:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Lihat Juga

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* antarmuka [IBaseSlide](../../../aspose.slides/ibaseslide)
* kelas [SlideUtil](../../slideutil)
* ruang nama [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Mengubah penempatan bentuk terpilih pada slide. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya secara relatif satu sama lain.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Menentukan jenis penyelarasan yang akan diterapkan. |
| alignToSlide | Boolean | Jika true, shape akan diselaraskan relatif terhadap tepi slide. |
| slide | IBaseSlide | Slide induk. |
| shapeIndexes | Int32[] | Indeks shape yang akan diselaraskan. |

### Contoh

Contoh:

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

### Lihat Juga

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* antarmuka [IBaseSlide](../../../aspose.slides/ibaseslide)
* kelas [SlideUtil](../../slideutil)
* ruang nama [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Mengubah penempatan semua bentuk dalam grup bentuk. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya secara relatif satu sama lain.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Menentukan jenis penyelarasan yang akan diterapkan. |
| alignToSlide | Boolean | Jika true, shape akan diselaraskan relatif terhadap tepi slide. |
| groupShape | IGroupShape | Grup bentuk induk. |

### Contoh

Contoh:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Lihat Juga

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* antarmuka [IGroupShape](../../../aspose.slides/igroupshape)
* kelas [SlideUtil](../../slideutil)
* ruang nama [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Mengubah penempatan bentuk terpilih dalam grup bentuk. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya secara relatif satu sama lain.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Menentukan jenis penyelarasan yang akan diterapkan. |
| alignToSlide | Boolean | Jika true, shape akan diselaraskan relatif terhadap tepi slide. |
| groupShape | IGroupShape | Grup bentuk induk. |
| shapeIndexes | Int32[] | Indeks shape yang akan diselaraskan. |

### Contoh

Contoh:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Lihat Juga

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* antarmuka [IGroupShape](../../../aspose.slides/igroupshape)
* kelas [SlideUtil](../../slideutil)
* ruang nama [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
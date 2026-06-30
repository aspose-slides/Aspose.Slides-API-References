---
title: AlignShapes
second_title: Aspose.Sildes .NET API referencia
description: Módosítja az összes alakzat elhelyezését a dián. Az alakzatokat a margókhoz vagy a dia széléhez igazítja, vagy egymáshoz viszonyítva igazítja.
type: docs
weight: 10
url: /hu/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Módosítja az összes alakzat elhelyezését a dián. Az alakzatokat a margókhoz vagy a dia széléhez igazítja, vagy egymáshoz viszonyítva igazítja.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Meghatározza, melyik igazítási típust kell alkalmazni. |
| alignToSlide | Boolean | Ha igaz, az alakzatok a diaszélekhez viszonyítva lesznek igazítva. |
| slide | IBaseSlide | Szülő dia. |

### Példák

Példa:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Lásd még

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* osztály [SlideUtil](../../slideutil)
* névtér [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Módosítja a kiválasztott alakzatok elhelyezését a dián. Az alakzatokat a margókhoz vagy a dia széléhez igazítja, vagy egymáshoz viszonyítva igazítja.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Meghatározza, melyik igazítási típust kell alkalmazni. |
| alignToSlide | Boolean | Ha igaz, az alakzatok a diaszélekhez viszonyítva lesznek igazítva. |
| slide | IBaseSlide | Szülő dia. |
| shapeIndexes | Int32[] | Az igazítandó alakzatok indexei. |

### Példák

Példa:

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

### Lásd még

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* osztály [SlideUtil](../../slideutil)
* névtér [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Módosítja az összes alakzat elhelyezését a csoport alakzaton belül. Az alakzatokat a margókhoz vagy a dia széléhez igazítja, vagy egymáshoz viszonyítva igazítja.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Meghatározza, melyik igazítási típust kell alkalmazni. |
| alignToSlide | Boolean | Ha igaz, az alakzatok a diaszélekhez viszonyítva lesznek igazítva. |
| groupShape | IGroupShape | Szülő csoport alakzat. |

### Példák

Példa:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Lásd még

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* osztály [SlideUtil](../../slideutil)
* névtér [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Módosítja a kiválasztott alakzatok elhelyezését a csoport alakzaton belül. Az alakzatokat a margókhoz vagy a dia széléhez igazítja, vagy egymáshoz viszonyítva igazítja.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Meghatározza, melyik igazítási típust kell alkalmazni. |
| alignToSlide | Boolean | Ha igaz, az alakzatok a diaszélekhez viszonyítva lesznek igazítva. |
| groupShape | IGroupShape | Szülő csoport alakzat. |
| shapeIndexes | Int32[] | Az igazítandó alakzatok indexei. |

### Példák

Példa:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Lásd még

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* osztály [SlideUtil](../../slideutil)
* névtér [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
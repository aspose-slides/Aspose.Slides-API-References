---
title: AlignShapes
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αλλάζει τη θέση όλων των σχημάτων στη διαφάνεια. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στο άκρο της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.
type: docs
weight: 10
url: /el/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Αλλάζει τη θέση όλων των σχημάτων στη διαφάνεια. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στο άκρο της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Καθορίζει ποιος τύπος στοίχισης θα εφαρμοστεί. |
| alignToSlide | Boolean | Εάν είναι true, τα σχήματα θα ευθυγραμμιστούν σε σχέση με τα άκρα της διαφάνειας. |
| slide | IBaseSlide | Διαφάνεια γονέας. |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Δείτε επίσης

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* διασύνδεση [IBaseSlide](../../../aspose.slides/ibaseslide)
* κλάση [SlideUtil](../../slideutil)
* χώρος ονομάτων [Aspose.Slides.Util](../../slideutil)
* συγκρότημα [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Αλλάζει τη θέση των επιλεγμένων σχημάτων στη διαφάνεια. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στο άκρο της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Καθορίζει ποιος τύπος στοίχισης θα εφαρμοστεί. |
| alignToSlide | Boolean | Εάν είναι true, τα σχήματα θα ευθυγραμμιστούν σε σχέση με τα άκρα της διαφάνειας. |
| slide | IBaseSlide | Διαφάνεια γονέας. |
| shapeIndexes | Int32[] | Δείκτες των σχημάτων που θα ευθυγραμμιστούν. |

### Παραδείγματα

Παράδειγμα:

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

### Δείτε επίσης

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* διασύνδεση [IBaseSlide](../../../aspose.slides/ibaseslide)
* κλάση [SlideUtil](../../slideutil)
* χώρος ονομάτων [Aspose.Slides.Util](../../slideutil)
* συγκρότημα [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Αλλάζει τη θέση όλων των σχημάτων μέσα σε ομάδα σχήματος. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στο άκρο της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Καθορίζει ποιος τύπος στοίχισης θα εφαρμοστεί. |
| alignToSlide | Boolean | Εάν είναι true, τα σχήματα θα ευθυγραμμιστούν σε σχέση με τα άκρα της διαφάνειας. |
| groupShape | IGroupShape | Γονική ομάδα σχήματος. |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Δείτε επίσης

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* διασύνδεση [IGroupShape](../../../aspose.slides/igroupshape)
* κλάση [SlideUtil](../../slideutil)
* χώρος ονομάτων [Aspose.Slides.Util](../../slideutil)
* συγκρότημα [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Αλλάζει τη θέση των επιλεγμένων σχημάτων μέσα σε ομάδα σχήματος. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στο άκρο της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Καθορίζει ποιος τύπος στοίχισης θα εφαρμοστεί. |
| alignToSlide | Boolean | Εάν είναι true, τα σχήματα θα ευθυγραμμιστούν σε σχέση με τα άκρα της διαφάνειας. |
| groupShape | IGroupShape | Γονική ομάδα σχήματος. |
| shapeIndexes | Int32[] | Δείκτες των σχημάτων που θα ευθυγραμμιστούν. |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Δείτε επίσης

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* διασύνδεση [IGroupShape](../../../aspose.slides/igroupshape)
* κλάση [SlideUtil](../../slideutil)
* χώρος ονομάτων [Aspose.Slides.Util](../../slideutil)
* συγκρότημα [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
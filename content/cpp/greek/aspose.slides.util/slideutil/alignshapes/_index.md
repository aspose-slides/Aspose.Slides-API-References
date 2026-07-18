---
title: AlignShapes()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αλλάζει τη θέση όλων των σχημάτων στη διαφάνεια. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στην άκρη της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.
type: docs
weight: 27
url: /el/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) method

Αλλάζει τη θέση όλων των σχημάτων στη διαφάνεια. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στην άκρη της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Καθορίζει ποιος τύπος ευθυγράμμισης θα εφαρμοστεί. |
| alignToSlide | **bool** | Αν είναι true, τα σχήματα θα ευθυγραμμιστούν σε σχέση με τις άκρες της διαφάνειας. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Γονική διαφάνεια. |

## Παρατηρήσεις



Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) method

Αλλάζει τη θέση των επιλεγμένων σχημάτων στη διαφάνεια. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στην άκρη της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Καθορίζει ποιος τύπος ευθυγράμμισης θα εφαρμοστεί. |
| alignToSlide | **bool** | Αν είναι true, τα σχήματα θα ευθυγραμμιστούν σε σχέση με τις άκρες της διαφάνειας. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Γονική διαφάνεια. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Δείκτες των σχημάτων που θα ευθυγραμμιστούν. |

## Παρατηρήσεις



Παράδειγμα: 
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) method

Αλλάζει τη θέση όλων των σχημάτων μέσα σε σχήμα ομάδας. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στην άκρη της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Καθορίζει ποιος τύπος ευθυγράμμισης θα εφαρμοστεί. |
| alignToSlide | **bool** | Αν είναι true, τα σχήματα θα ευθυγραμμιστούν σε σχέση με τις άκρες της διαφάνειας. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Γονικό σχήμα ομάδας. |

## Παρατηρήσεις



Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) method

Αλλάζει τη θέση των επιλεγμένων σχημάτων μέσα σε σχήμα ομάδας. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στην άκρη της διαφάνειας ή τα ευθυγραμμίζει μεταξύ τους.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Καθορίζει ποιος τύπος ευθυγράμμισης θα εφαρμοστεί. |
| alignToSlide | **bool** | Αν είναι true, τα σχήματα θα ευθυγραμμιστούν σε σχέση με τις άκρες της διαφάνειας. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Γονικό σχήμα ομάδας. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Δείκτες των σχημάτων που θα ευθυγραμμιστούν. |

## Παρατηρήσεις



Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## Δείτε επίσης

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [SlideUtil](../)
* Class [IGroupShape](../../../aspose.slides/igroupshape/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)
---
title: SlideUtil
second_title: Αναφορά API του Aspose.Slides για C++
description: Προσφέρει μεθόδους που βοηθούν στην αναζήτηση σχημάτων και κειμένου σε μια παρουσίαση.
type: docs
weight: 14
url: /el/aspose.slides.util/slideutil/
---
## SlideUtil κλάση

Προσφέρει μεθόδους που βοηθούν στην αναζήτηση σχημάτων και κειμένου σε μια παρουσίαση.

```cpp
class SlideUtil
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Αλλάζει την τοποθέτηση όλων των σχημάτων στη διαφάνεια. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στην άκρη της διαφάνειας ή τα ευθυγραμμίζει σχετικά μεταξύ τους. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Αλλάζει την τοποθέτηση των επιλεγμένων σχημάτων στη διαφάνεια. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στην άκρη της διαφάνειας ή τα ευθυγραμμίζει σχετικά μεταξύ τους. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | Αλλάζει την τοποθέτηση όλων των σχημάτων μέσα σε ομάδα σχημάτων. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στην άκρη της διαφάνειας ή τα ευθυγραμμίζει σχετικά μεταξύ τους. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Αλλάζει την τοποθέτηση των επιλεγμένων σχημάτων μέσα σε ομάδα σχημάτων. Ευθυγραμμίζει τα σχήματα στα περιθώρια ή στην άκρη της διαφάνειας ή τα ευθυγραμμίζει σχετικά μεταξύ τους. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | Βρίσκει και αντικαθιστά κείμενο στην παρουσίαση με δοσμένη μορφή |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | Βρίσκει σχήμα με εναλλακτικό κείμενο σε παρουσίαση PPTX. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | Βρίσκει σχήμα με εναλλακτικό κείμενο σε μια διαφάνεια σε παρουσίαση PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | Αναζητά όλα τα σχήματα στη συγκεκριμένη διαφάνεια που ταιριάζουν με τον δεδομένο τύπο δείκτη. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Επιστρέφει όλα τα πλαίσια κειμένου σε μια διαφάνεια σε παρουσίαση PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | Επιστρέφει όλα τα πλαίσια κειμένου σε παρουσίαση PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | Επιστρέφει όλα τα πλαίσια κειμένου στη συγκεκριμένη διαφάνεια που περιέχουν το δεδομένο κείμενο. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | Μετατρέπει μια μορφή αρχείου προέλευσης στην αντίστοιχη [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/). |

## Δείτε επίσης

* Χώρος ονομάτων [Aspose::Slides::Util](../)
* Βιβλιοθήκη [Aspose.Slides](../../)
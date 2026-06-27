---
title: Cell
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αντιπροσωπεύει ένα κελί ενός πίνακα.
type: docs
weight: 1110
url: /el/aspose.slides/cell/
---
## Cell κλάση

Αντιπροσωπεύει ένα κελί ενός πίνακα.

```csharp
public class Cell : ICell
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Καθορίζει εάν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Ανάγνωση/Εγγραφή Boolean. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Επιστρέφει το CellFormat object που περιέχει ιδιότητες μορφοποίησης για αυτό το κελί. Μόνο ανάγνωση [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Επιστρέφει τον αριθμό των στηλών του πλέγματος του γονικού πίνακα που πρέπει να καλυφθούν από το τρέχον κελί. Αυτή η ιδιότητα επιτρέπει στα κελιά να φαίνονται συγχωνευμένα, καθώς καλύπτουν κάθετες όρια άλλων κελιών στον πίνακα. Μόνο ανάγνωση Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Παίρνει την πρώτη στήλη του κελιού. Μόνο ανάγνωση [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Επιστρέφει έναν δείκτη της πρώτης στήλης που καλύπτεται από το κελί. Μόνο ανάγνωση Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Παίρνει την πρώτη γραμμή του κελιού. Μόνο ανάγνωση [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Επιστρέφει έναν δείκτη της πρώτης γραμμής που καλύπτεται από το κελί. Μόνο ανάγνωση Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Επιστρέφει το ύψος του κελιού. Μόνο ανάγνωση Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Επιστρέφει true αν το κελί είναι συγχωνευμένο με οποιοδήποτε προσαρμοσμένο κελί, false διαφορετικά. Μόνο ανάγνωση Boolean. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. Ανάγνωση/Εγγραφή Double. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. Ανάγνωση/Εγγραφή Double. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Επιστρέφει ή ορίζει το δεξί περιθώριο σε ένα TextFrame. Ανάγνωση/Εγγραφή Double. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Επιστρέφει ή ορίζει το πάνω περιθώριο σε ένα TextFrame. Ανάγνωση/Εγγραφή Double. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Επιστρέφει το ελάχιστο ύψος ενός κελιού. Αυτό είναι το άθροισμα των ελάχιστων υψών όλων των γραμμών που καλύπτονται από το κελί. Μόνο ανάγνωση Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Επιστρέφει την απόσταση από την αριστερή πλευρά ενός πίνακα στην αριστερή πλευρά ενός κελιού. Μόνο ανάγνωση Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Επιστρέφει την απόσταση από την πάνω πλευρά ενός πίνακα στην πάνω πλευρά ενός κελιού. Μόνο ανάγνωση Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Επιστρέφει την γονική παρουσίαση ενός κελιού. Μόνο ανάγνωση [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Επιστρέφει τον αριθμό των γραμμών που καλύπτει ένα συγχωνευμένο κελί. Αυτό χρησιμοποιείται σε συνδυασμό με το χαρακτηριστικό vMerge σε άλλα κελιά για να καθορίσει το αρχικό κελί μιας οριζόντιας συγχώνευσης. Μόνο ανάγνωση Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός κελιού. Μόνο ανάγνωση [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Επιστρέφει το γονικό αντικείμενο Table για ένα κελί. Μόνο ανάγνωση [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο άγκυρας κειμένου. Ανάγνωση/Εγγραφή [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Επιστρέφει το πλαίσιο κειμένου ενός κελιού. Μόνο ανάγνωση [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο του κατακόρυφου κειμένου. Ανάγνωση/Εγγραφή [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Επιστρέφει το πλάτος του κελιού. Μόνο ανάγνωση Double. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Διαιρεί το κελί σε δύο κελιά κατά δείκτη στήλης. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Διαιρεί το κελί κατά ύψος. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Διαιρεί το κελί σε δύο κελιά κατά δείκτη γραμμής. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Διαιρεί το κελί κατά πλάτος. |

### Δείτε επίσης

* διεπαφή [ICell](../icell)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
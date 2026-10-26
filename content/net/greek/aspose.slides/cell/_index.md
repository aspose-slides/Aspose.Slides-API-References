---
title: Cell
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει ένα κελί ενός πίνακα.
type: docs
weight: 1130
url: /el/aspose.slides/cell/
---
## Κλάση Cell

Αντιπροσωπεύει ένα κελί ενός πίνακα.

```csharp
public class Cell : ICell
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Ανάγνωση/εγγραφή Boolean. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Επιστρέφει το αντικείμενο CellFormat που περιέχει ιδιότητες μορφοποίησης για αυτό το κελί. Μόνο για ανάγνωση [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Επιστρέφει τον αριθμό των στηλών πλέγματος στον πίνακα-γονέα που καλύπτονται από το τρέχον κελί. Αυτή η ιδιότητα επιτρέπει στα κελιά να φαίνονται συγχωνευμένα, καθώς καλύπτουν κάθετες περιοχές άλλων κελιά στον πίνακα. Μόνο για ανάγνωση Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Λαμβάνει την πρώτη στήλη του κελιού. Μόνο για ανάγνωση [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Επιστρέφει το δείκτη της πρώτης στήλης που καλύπτεται από το κελί. Μόνο για ανάγνωση Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Λαμβάνει την πρώτη γραμμή του κελιού. Μόνο για ανάγνωση [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Επιστρέφει το δείκτη της πρώτης γραμμής που καλύπτεται από το κελί. Μόνο για ανάγνωση Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Επιστρέφει το ύψος του κελιού. Μόνο για ανάγνωση Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Επιστρέφει true εάν το κελί είναι συγχωνευμένο με κάποιο προσαρμοσμένο κελί, false διαφορετικά. Μόνο για ανάγνωση Boolean. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Επιστρέφει ή ορίζει το δεξιό περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Επιστρέφει ή ορίζει το άνω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Επιστρέφει το ελάχιστο ύψος ενός κελιού. Αυτό είναι το άθροισμα των ελάχιστων υψών όλων των γραμμών που καλύπτονται από το κελί. Μόνο για ανάγνωση Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Επιστρέφει την απόσταση από την αριστερή πλευρά του πίνακα έως την αριστερή πλευρά του κελιού. Μόνο για ανάγνωση Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Επιστρέφει την απόσταση από την άνω πλευρά του πίνακα έως την άνω πλευρά του κελιού. Μόνο για ανάγνωση Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Επιστρέφει την παρουσίαση-γονέα ενός κελιού. Μόνο για ανάγνωση [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Επιστρέφει τον αριθμό των γραμμών που καλύπτει ένα συγχωνευμένο κελί. Χρησιμοποιείται σε συνδυασμό με το χαρακτηριστικό vMerge σε άλλα κελιά για να ορίσει το αρχικό κελί μιας οριζόντιας συγχώνευσης. Μόνο για ανάγνωση Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Επιστρέφει τη διαφάνεια-γονέα ενός κελιού. Μόνο για ανάγνωση [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Επιστρέφει το αντικείμενο Table-γονέα για ένα κελί. Μόνο για ανάγνωση [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο αγκύρωσης κειμένου. Ανάγνωση/εγγραφή [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Επιστρέφει το TextFrame ενός κελιού. Μόνο για ανάγνωση [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο του κάθετου κειμένου. Ανάγνωση/εγγραφή [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Επιστρέφει το πλάτος του κελιού. Μόνο για ανάγνωση Double. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Διαχωρίζει το κελί σε δύο κελιά με βάση το δείκτη στήλης. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Διαχωρίζει το κελί ανά ύψος. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Διαχωρίζει το κελί σε δύο κελιά με βάση το δείκτη γραμμής. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Διαχωρίζει το κελί ανά πλάτος. |

### Δείτε επίσης

* διασύνδεση [ICell](../icell)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
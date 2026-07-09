---
title: ICell
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει ένα κελί σε έναν πίνακα.
type: docs
weight: 5450
url: /el/aspose.slides/icell/
---
## ICell διασύνδεση

Αντιπροσωπεύει ένα κελί σε έναν πίνακα.

```csharp
public interface ICell : ISlideComponent
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί. Ανάγνωση/εγγραφή Boolean. |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Επιτρέπει την ανάκτηση της βασικής διασύνδεσης ISlideComponent. Μόνο ανάγνωση [`ISlideComponent`](../islidecomponent). |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Επιστρέφει το αντικείμενο CellFormat που περιέχει ιδιότητες μορφοποίησης για αυτό το κελί. Μόνο ανάγνωση [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Επιστρέφει τον αριθμό των στηλών πλέγματος του γονικού πίνακα που καλύπτονται από το τρέχον κελί. Αυτή η ιδιότητα επιτρέπει στα κελιά να έχουν την εμφάνιση συγχώνευσης, καθώς εκτείνονται πάνω από κάθετες διαχωριστικές γραμμές άλλων κελιών στον πίνακα. Μόνο ανάγνωση Int32. |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Αποκτά την πρώτη στήλη του κελιού. Μόνο ανάγνωση [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Επιστρέφει έναν δείκτη της πρώτης στήλης που καλύπτεται από το κελί. Μόνο ανάγνωση Int32. |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Αποκτά την πρώτη γραμμή του κελιού. Μόνο ανάγνωση [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Επιστρέφει έναν δείκτη της πρώτης γραμμής που καλύπτεται από το κελί. Μόνο ανάγνωση Int32. |
| [Height](../../aspose.slides/icell/height) { get; } | Επιστρέφει το ύψος του κελιού. Μόνο ανάγνωση Double. |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Επιστρέφει true εάν το κελί είναι συγχωνευμένο με οποιοδήποτε προσαρμοσμένο κελί, false διαφορετικά. Μόνο ανάγνωση Boolean. |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Επιστρέφει ή ορίζει το δεξιό περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Επιστρέφει ή ορίζει το άνω περιθώριο σε ένα TextFrame. Ανάγνωση/εγγραφή Double. |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Επιστρέφει το ελάχιστο ύψος ενός κελιού. Αυτό είναι το άθροισμα των ελάχιστων υψών όλων των γραμμών που καλύπτονται από το κελί. Μόνο ανάγνωση Double. |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Επιστρέφει την απόσταση από την αριστερή πλευρά του πίνακα έως την αριστερή πλευρά του κελιού. Μόνο ανάγνωση Double. |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Επιστρέφει την απόσταση από την πάνω πλευρά του πίνακα έως την πάνω πλευρά του κελιού. Μόνο ανάγνωση Double. |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Επιστρέφει τον αριθμό των γραμμών που καλύπτει ένα συγχωνευμένο κελί. Αυτό χρησιμοποιείται σε συνδυασμό με το χαρακτηριστικό vMerge σε άλλα κελιά για να καθορίσει το αρχικό κελί μιας οριζόντιας συγχώνευσης. Μόνο ανάγνωση Int32. |
| [Table](../../aspose.slides/icell/table) { get; } | Επιστρέφει το γονικό αντικείμενο Table για ένα κελί. Μόνο ανάγνωση [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο αγκύρωσης κειμένου. Ανάγνωση/εγγραφή [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Επιστρέφει το πλαίσιο κειμένου ενός κελιού. Μόνο ανάγνωση [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο κάθετου κειμένου. Ανάγνωση/εγγραφή [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/icell/width) { get; } | Επιστρέφει το πλάτος του κελιού. Μόνο ανάγνωση Double. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Διαιρεί το κελί σε δύο κελιά με βάση τον δείκτη στήλης. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Διαιρεί το κελί κατά ύψος. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Διαιρεί το κελί σε δύο κελιά με βάση τον δείκτη γραμμής. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Διαιρεί το κελί κατά πλάτος. |

### Δείτε επίσης

* διασύνδεση [ISlideComponent](../islidecomponent)
* ονομαχώρος [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
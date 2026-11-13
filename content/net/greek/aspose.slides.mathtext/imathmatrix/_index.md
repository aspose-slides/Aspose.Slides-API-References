---
title: IMathMatrix
second_title: Aspose.Sildes για .NET Αναφορά API
description: Καθορίζει το αντικείμενο Matrix που αποτελείται από στοιχεία-παιδιά τοποθετημένα σε μία ή περισσότερες γραμμές και στήλες. Είναι σημαντικό να σημειωθεί ότι τα matrices δεν διαθέτουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε το matrix σε αγκύλες θα πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη IMathDelimiter. Μπορούν να χρησιμοποιηθούν null επιχειρήματα για τη δημιουργία κενών στα matrices.
type: docs
weight: 8360
url: /el/aspose.slides.mathtext/imathmatrix/
---
## Διασύνδεση IMathMatrix

Καθορίζει το αντικείμενο Matrix, που αποτελείται από στοιχεία-παιδιά ταυτοποιημένα σε μία ή περισσότερες γραμμές και στήλες. Είναι σημαντικό να σημειωθεί ότι τα matrices δεν έχουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε το matrix σε αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter). Μπορούν να χρησιμοποιηθούν null επιχειρήματα για τη δημιουργία κενών στα matrices.

```csharp
public interface IMathMatrix : IMathElement
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Επιτρέπει την απόκτηση της βασικής διεπαφής IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Καθορίζει την κάθετη στοίχιση σε σχέση με το περιβάλλον κείμενο. Οι δυνατές τιμές είναι top, bottom, and center. Προεπιλογή: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Αριθμός στηλών στον πίνακα |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· εάν το ColumnGapRule είναι ορισμένο σε 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule είναι ορισμένο σε 4 ("Multiple"), η μονάδα ερμηνεύεται ως αριθμός 0,5 em βημάτων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Ο τύπος της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· οι μονάδες οριζόντιας απόστασης μπορούν να είναι ems ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Απόκρυψη των θέσεων κράτησης για κενά στοιχεία του πίνακα Προεπιλογή: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Στοιχεία του πίνακα |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου) Η απόσταση κενού (επίσης αναφερόμενη ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού διάστηματος στηλών του πίνακα (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Αριθμός γραμμών στον πίνακα |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Η τιμή της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· εάν το RowGapRule είναι ορισμένο σε 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule είναι ορισμένο σε 4 ("Multiple"), η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Ο τύπος της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· οι μονάδες κάθετης απόστασης μπορούν να είναι lines ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Διαγράφει τη συγκεκριμένη στήλη |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Διαγράφει τη συγκεκριμένη γραμμή |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Επιστρέφει την οριζόντια στοίχιση της συγκεκριμένης στήλης |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Εισάγει μια νέα στήλη μετά τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Εισάγει μια νέα στήλη πριν τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Εισάγει μια νέα γραμμή μετά τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Εισάγει μια νέα γραμμή πριν τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ορίζει την οριζόντια στοίχιση της συγκεκριμένης στήλης |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ορίζει την οριζόντια στοίχιση των συγκεκριμένων στηλών |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Δείτε επίσης

* διασύνδεση [IMathElement](../imathelement)
* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
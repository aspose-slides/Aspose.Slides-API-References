---
title: IMathMatrix
second_title: Aspose.Sildes για .NET API Reference
description: Καθορίζει το αντικείμενο Matrix που αποτελείται από στοιχεία-παιδιά τοποθετημένα σε μία ή περισσότερες σειρές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν έχουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη IMathDelimiter. Μπορούν να χρησιμοποιηθούν null ορίσματα για τη δημιουργία κενών στους πίνακες.
type: docs
weight: 8340
url: /el/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix διασύνδεση

Καθορίζει το αντικείμενο Matrix, το οποίο αποτελείται από στοιχεία-παιδιά τακτοποιημένα σε μία ή περισσότερες σειρές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν διαθέτουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες, πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter). Τα μηδενικά ορίσματα μπορούν να χρησιμοποιηθούν για τη δημιουργία κενών στους πίνακες.

```csharp
public interface IMathMatrix : IMathElement
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Επιτρέπει την ανάκτηση της βασικής διεπαφής IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Οι δυνατές τιμές είναι top, bottom, και center. Προεπιλογή: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Αριθμός στηλών στον πίνακα |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός πίνακα· εάν το ColumnGapRule έχει τιμή 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) εάν το RowGapRule έχει τιμή 4 ("Multiple"), η μονάδα ερμηνεύεται ως αριθμός 0.5 em αυξήσεων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Ο τύπος του οριζόντιου διαστήματος μεταξύ των στηλών ενός πίνακα· οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Απόκρυψη των καταχωρητών θέσης για κενά στοιχεία πίνακα Προεπιλογή: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Στοιχεία του πίνακα |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου) Το κενό μεταξύ (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού διαστήματος στηλών του πίνακα (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Αριθμός σειρών στον πίνακα |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Η τιμή του κατακόρυφου διαστήματος μεταξύ των σειρών ενός πίνακα· εάν το RowGapRule έχει τιμή 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου) εάν το RowGapRule έχει τιμή 4 ("Multiple"), η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Ο τύπος του κατακόρυφου διαστήματος μεταξύ των σειρών ενός πίνακα· οι μονάδες κατακόρυφου διαστήματος μπορούν να είναι lines ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Διαγράφει τη συγκεκριμένη στήλη |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Διαγράφει τη συγκεκριμένη σειρά |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Λαμβάνει την οριζόντια στοίχιση της συγκεκριμένης στήλης |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Εισάγει μια νέα στήλη μετά τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Εισάγει μια νέα στήλη πριν τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Εισάγει μια νέα σειρά μετά τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα σειρά είναι null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Εισάγει μια νέα σειρά πριν τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα σειρά είναι null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ορίζετε την οριζόντια στοίχιση της συγκεκριμένης στήλης |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ορίζετε την οριζόντια στοίχιση των συγκεκριμένων στηλών |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Δείτε επίσης

* διασύνδεση [IMathElement](../imathelement)
* χώρος ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* σύνολο [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
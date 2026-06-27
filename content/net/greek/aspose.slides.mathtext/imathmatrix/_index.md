---
title: IMathMatrix
second_title: Aspose.Sildes για .NET API Αναφορά
description: Καθορίζει το αντικείμενο Matrix που αποτελείται από θυγατρικά στοιχεία διατεταγμένα σε μία ή περισσότερες γραμμές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν έχουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη IMathDelimiter. Μηδενικά επιχειρήματα μπορούν να χρησιμοποιηθούν για τη δημιουργία κενών στους πίνακες.
type: docs
weight: 8320
url: /el/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix διεπαφή

Καθορίζει το αντικείμενο Matrix, που αποτελείται από θυγατρικά στοιχεία διατεταγμένα σε μία ή περισσότερες γραμμές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν διαθέτουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter). Μπορούν να χρησιμοποιηθούν μηδενικά επιχειρήματα για τη δημιουργία κενών στα πίνακες.

```csharp
public interface IMathMatrix : IMathElement
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Επιτρέπει την ανάκτηση της βασικής διεπαφής IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Καθορίζει την κάθετη στοίχιση σε σχέση με το κείμενο γύρω. Πιθανές τιμές είναι top, bottom, και center. Προεπιλογή: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Αριθμός στηλών στο πίνακα |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Η τιμή της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Εάν το ColumnGapRule είναι ορισμένο σε 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule είναι ορισμένο σε 4 ("Multiple"), η μονάδα ερμηνεύεται ως αριθμός των βημάτων 0.5 em. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Ο τύπος της οριζόντιας απόστασης μεταξύ των στηλών ενός πίνακα· Οι μονάδες οριζόντιας απόστασης μπορεί να είναι ems ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Απόκρυψη των δεσμευτών θέσης για κενά στοιχεία του πίνακα. Προεπιλογή: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Στοιχεία του πίνακα |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Η απόσταση του κενού (επίσης αναφέρεται ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για να καθορίσει τη συνολική απόσταση στηλών του πίνακα (απόσταση μεταξύ των ίδιων ακρών διαφορετικών στηλών). Προεπιλογή: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Αριθμός γραμμών στο πίνακα |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Η τιμή της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Εάν το RowGapRule είναι ορισμένο σε 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule είναι ορισμένο σε 4 ("Multiple"), η μονάδα ερμηνεύεται ως half-lines. Προεπιλογή: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Ο τύπος της κάθετης απόστασης μεταξύ των γραμμών ενός πίνακα· Οι μονάδες κάθετης απόστασης μπορεί να είναι lines ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Διαγράφει τη συγκεκριμένη στήλη |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Διαγράφει τη συγκεκριμένη γραμμή |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Αποκτά την οριζόντια στοίχιση της συγκεκριμένης στήλης |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Εισάγει μια νέα στήλη μετά τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Εισάγει μια νέα στήλη πριν τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Εισάγει μια νέα γραμμή μετά τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Εισάγει μια νέα γραμμή πριν τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ορίζει την οριζόντια στοίχιση της συγκεκριμένης στήλης |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ορίζει την οριζόντια στοίχιση των συγκεκριμένων στηλών |

### Παραδείγματα

Example:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Δείτε επίσης

* διεπαφή [IMathElement](../imathelement)
* χώρος ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
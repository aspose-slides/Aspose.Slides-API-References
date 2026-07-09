---
title: MathMatrix
second_title: Aspose.Sildes για .NET API αναφορά
description: Καθορίζει το αντικείμενο Matrix που αποτελείται από θυγατρικά στοιχεία διατεταγμένα σε μία ή περισσότερες σειρές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν έχουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη IMathDelimiter. Τα ορίσματα null μπορούν να χρησιμοποιηθούν για τη δημιουργία κενών στους πίνακες.
type: docs
weight: 8850
url: /el/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix κλάση

Καθορίζει το αντικείμενο Matrix, το οποίο αποτελείται από θυγατρικά στοιχεία διατεταγμένα σε μία ή περισσότερες σειρές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν έχουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter). Μπορούν να χρησιμοποιηθούν παράμετροι null για τη δημιουργία κενών στους πίνακες.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathMatrix. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Καθορίζει την κάθετη στοίχιση σε σχέση με το περιβάλλον κείμενο. Οι δυνατές τιμές είναι top, bottom και center. Προεπιλογή: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Αριθμός στηλών στον πίνακα |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Η τιμή της οριζόντιας απόστασης μεταξύ στηλών ενός πίνακα· εάν το ColumnGapRule είναι ορισμένο σε 3 ("Exactly"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule είναι ορισμένο σε 4 ("Multiple"), τότε η μονάδα ερμηνεύεται ως αριθμός 0.5 em αυξήσεων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Ο τύπος της οριζόντιας απόστασης μεταξύ στηλών ενός πίνακα· οι μονάδες οριζόντιας απόστασης μπορούν να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Απόκρυψη των εικονικών χαρακτήρων για κενά στοιχεία του πίνακα. Προεπιλογή: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Στοιχείο του πίνακα |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Η απόσταση του κενών (επίσης γνωστή ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για τον καθορισμό του συνολικού διαστήματος στήλης του πίνακα (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Αριθμός σειρών στον πίνακα |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Η τιμή της κάθετης απόστασης μεταξύ σειρών ενός πίνακα· εάν το RowGapRule είναι ορισμένο σε 3 ("Exactly"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule είναι ορισμένο σε 4 ("Multiple"), τότε η μονάδα ερμηνεύεται ως half-lines. Προεπιλογή: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Ο τύπος της κάθετης απόστασης μεταξύ σειρών ενός πίνακα· οι μονάδες κάθετης απόστασης μπορούν να είναι lines ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα διακριτικό σημάδι (χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Εκτελεί τη συγκεκριμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Εκτελεί τη συγκεκριμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Εκτελεί τη συγκεκριμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Εκτελεί τη συγκεκριμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Εκτελεί τη συγκεκριμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Διαγράφει την καθορισμένη στήλη |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Διαγράφει την καθορισμένη σειρά |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Περιβάλλει ένα μαθηματικό στοιχείο σε συγκεκριμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Εκτελεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Εκτελεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Παίρνει τα θυγατρικά στοιχεία |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Παίρνει την οριζόντια στοίχιση της καθορισμένης στήλης |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας αγκυλεπόδεση στο κάτω μέρος |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως αγκυλεπόδεση στο κάτω μέρος ή άλλο |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Εισάγει μια νέα στήλη μετά την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Εισάγει μια νέα στήλη πριν την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Εισάγει μια νέα σειρά μετά την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα σειρά είναι null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Εισάγει μια νέα σειρά πριν την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα σειρά είναι null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Πραγματοποιεί το ολοκληρωματικό χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Πραγματοποιεί το ολοκληρωματικό |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Πραγματοποιεί το ολοκληρωματικό |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Πραγματοποιεί το ολοκληρωματικό |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Πραγματοποιεί το ολοκληρωματικό |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Συνδυάζει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Συνδυάζει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Τοποθετεί μια γραμμή στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ορίζει την οριζόντια στοίχιση της καθορισμένης στήλης |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ορίζει την οριζόντια στοίχιση των καθορισμένων στηλών |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Λαμβάνει το κατώτερο όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Λαμβάνει το κατώτερο όριο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί δείκτη |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί δείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί εκθέτη |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί εκθέτη |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Λαμβάνει το ανώτερο όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Λαμβάνει το ανώτερο όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε κουτί-περίγραμμα |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε κουτί-περίγραμμα |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για την ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου μαθηματικού κειμένου. Ένα αντικείμενο σε κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να λειτουργήσει ως σημείο διακοπής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπει αλλαγές γραμμής μέσα σε αυτό. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κάθετη διάταξη |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Τοποθετεί μια γραμμή στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διασύνδεση [IMathMatrix](../imathmatrix)
* χώρος ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
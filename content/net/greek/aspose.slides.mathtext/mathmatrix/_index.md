---
title: MathMatrix
second_title: Aspose.Sildes για .NET API Reference
description: Καθορίζει το αντικείμενο Matrix που αποτελείται από θυγατρικά στοιχεία τοποθετημένα σε μία ή περισσότερες σειρές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν διαθέτουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες, θα πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη IMathDelimiter. Μπορούν να χρησιμοποιηθούν κενά ορίσματα για τη δημιουργία κενών στους πίνακες.
type: docs
weight: 8830
url: /el/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix κλάση

Καθορίζει το αντικείμενο Matrix, το οποίο αποτελείται από θυγατρικά στοιχεία που τοποθετούνται σε μια ή περισσότερες σειρές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν διαθέτουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες, πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter). Μπορούν να χρησιμοποιηθούν κενά ορίσματα για τη δημιουργία κενών στον πίνακα.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Αρχικοποιεί μια νέα παρουσία της κλάσης MathMatrix. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom, και center. Προεπιλογή: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Αριθμός στηλών στον πίνακα |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός πίνακα· εάν το ColumnGapRule είναι ορισμένο σε 3 ("Exactly"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το ColumnGapRule είναι ορισμένο σε 4 ("Multiple"), τότε η μονάδα ερμηνεύεται ως αριθμός 0.5 em βημάτων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Ο τύπος του οριζόντιου διαστήματος μεταξύ των στηλών ενός πίνακα· οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Απόκρυψη των εικονικών θέσεων για κενά στοιχεία του πίνακα. Προεπιλογή: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Στοιχείο του πίνακα |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το διάστημα του κενά (επίσης αναφερόμενο ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για να καθορίσει το συνολικό διάστημα Στήλης Πίνακα (απόσταση μεταξύ των ίδιων άκρων διαφορετικών στηλών). Προεπιλογή: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Αριθμός γραμμών στον πίνακα |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Η τιμή του κατακόρυφου διαστήματος μεταξύ των γραμμών ενός πίνακα· εάν το RowGapRule είναι ορισμένο σε 3 ("Exactly"), τότε η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Εάν το RowGapRule είναι ορισμένο σε 4 ("Multiple"), τότε η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Ο τύπος του κατακόρυφου διαστήματος μεταξύ των γραμμών ενός πίνακα· οι μονάδες κατακόρυφου διαστήματος μπορούν να είναι lines ή points (αποθηκευμένες ως twips). Προεπιλογή: SingleSpacingGap (0) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα διακριτικό (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Δέχεται την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Δέχεται την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Δέχεται την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Δέχεται την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Δέχεται την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Διαγράφει την καθορισμένη στήλη |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Διαγράφει την καθορισμένη γραμμή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Τοποθετεί ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαισίωση |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Δέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την παρουσία ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Δέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την παρουσία ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Λαμβάνει τα θυγατρικά στοιχεία |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Λαμβάνει την οριζόντια στοίχιση της καθορισμένης στήλης |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κατιούσα αγκύλη |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως κατιούσα αγκύλη ή άλλον |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Εισάγει μια νέα στήλη μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Εισάγει μια νέα στήλη πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Εισάγει μια νέα γραμμή μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Εισάγει μια νέα γραμμή πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Δέχεται το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Δέχεται το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Δέχεται το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Δέχεται το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Δέχεται το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Θέτει μια γραμμή στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ορίζει την οριζόντια στοίχιση της καθορισμένης στήλης |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ορίζει την οριζόντια στοίχιση των καθορισμένων στηλών |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Δέχεται το κατώτερο όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Δέχεται το κατώτερο όριο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί υπόγραμμο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί υπόγραμμο |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί υπόγραμμο και υπεργράμμο στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί υπόγραμμο και υπεργράμμο στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί υπόγραμμο και υπεργράμμο στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί υπόγραμμο και υπεργράμμο στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί υπεργράμμο |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί υπεργράμμο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Δέχεται το ανώτερο όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Δέχεται το ανώτερο όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περιθώριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περιθώριο |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης περίπτωσης μαθηματικού κειμένου. Ένα κουτί-αντικείμενο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να λειτουργήσει ως σημείο διακοπής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπει τη διάσπαση γραμμής μέσα σε αυτό. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κατακόρυφο πίνακα |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Θέτει μια γραμμή στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Example:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διασύνδεση [IMathMatrix](../imathmatrix)
* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
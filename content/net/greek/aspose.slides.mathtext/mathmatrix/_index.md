---
title: MathMatrix
second_title: Aspose.Sildes για .NET API Αναφορά
description: Καθορίζει το αντικείμενο Matrix που αποτελείται από στοιχεία-παιδιά τοποθετημένα σε μία ή περισσότερες γραμμές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν έχουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη IMathDelimiter. Μπορούν να χρησιμοποιηθούν null ορίσματα για τη δημιουργία κενών στους πίνακες.
type: docs
weight: 8870
url: /el/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix κλάση

Καθορίζει το αντικείμενο Matrix, που αποτελείται από στοιχεία-παιδιά τοποθετημένα σε μία ή περισσότερες γραμμές και στήλες. Είναι σημαντικό να σημειωθεί ότι οι πίνακες δεν έχουν ενσωματωμένους οριοθέτες. Για να τοποθετήσετε τον πίνακα σε αγκύλες πρέπει να χρησιμοποιήσετε το αντικείμενο οριοθέτη (IMathDelimiter). Μπορούν να χρησιμοποιηθούν null ορίσματα για να δημιουργηθούν κενά στους πίνακες.

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
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Οι δυνατές τιμές είναι top, bottom και center. Προεπιλογή: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Αριθμός στηλών στον πίνακα |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Η τιμή του οριζόντιου διαστήματος μεταξύ των στηλών ενός πίνακα· αν το ColumnGapRule έχει τιμή 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το ColumnGapRule έχει τιμή 4 ("Multiple"), η μονάδα ερμηνεύεται ως αριθμός 0.5 em βημάτων. Σε άλλες περιπτώσεις αγνοείται. Προεπιλογή: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Ο τύπος του οριζόντιου διαστήματος μεταξύ των στηλών ενός πίνακα· Οι μονάδες οριζόντιου διαστήματος μπορούν να είναι ems ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Απόκρυψη των δεσμευτών θέσεων για κενά στοιχεία πίνακα. Προεπιλογή: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Στοιχείο του πίνακα |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Ελάχιστο πλάτος στήλης σε twips (1/20 του σημείου). Το κενό διάστημα (επίσης αναφερόμενο ως “Column Gap” ή “Gap Width”) προστίθεται στο MinColumnWidth για να καθορίσει το συνολικό Διάστημα Στήλης του Πίνακα (απόσταση μεταξύ των ίδιας άκρων διαφορετικών στηλών). Προεπιλογή: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Αριθμός γραμμών στον πίνακα |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Η τιμή του κατακόρυφου διαστήματος μεταξύ των γραμμών ενός πίνακα· αν το RowGapRule έχει τιμή 3 ("Exactly"), η μονάδα ερμηνεύεται ως twips (1/20 του σημείου). Αν το RowGapRule έχει τιμή 4 ("Multiple"), η μονάδα ερμηνεύεται ως μισές γραμμές. Προεπιλογή: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Ο τύπος του κατακόρυφου διαστήματος μεταξύ των γραμμών ενός πίνακα· Οι μονάδες κατακόρυφου διαστήματος μπορούν να είναι lines ή points (αποθηκευμένα ως twips). Προεπιλογή: SingleSpacingGap (0) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σημάδι τονισμού (χαρακτήρας στην κορυφή αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Διαγράφει την καθορισμένη στήλη |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Διαγράφει την καθορισμένη γραμμή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τοποθετεί ένα μαθηματικό στοιχείο μέσα σε παρένθεση |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Τοποθετεί ένα μαθηματικό στοιχείο μέσα σε καθορισμένους χαρακτήρες, όπως παρένθεση ή άλλους χαρακτήρες ως πλαισίωση |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Εκτελεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Εκτελεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Λαμβάνει τα στοιχεία-παιδιά |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Λαμβάνει την οριζόντια ευθυγράμμιση της καθορισμένης στήλης |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη σπασίλας |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης, όπως η κάτω αγκύλη σπασίλας ή άλλος |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Εισάγει νέα στήλη μετά την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Εισάγει νέα στήλη πριν την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Εισάγει νέα γραμμή μετά την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Εισάγει νέα γραμμή πριν την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Εκτελεί το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Εκτελεί το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Εκτελεί το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Εκτελεί το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Εκτελεί το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Συμπλέκει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Συμπλέκει μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Τοποθετεί μια γραμμή επάνω από αυτό το στοιχείο |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ορίζει την οριζόντια ευθυγράμμιση της καθορισμένης στήλης |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ορίζει την οριζόντια ευθυγράμμιση των καθορισμένων στηλών |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Εκτελεί το κάτω όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Εκτελεί το κάτω όριο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί δείκτη |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί δείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί εκθέτη |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί εκθέτη |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Εκτελεί το άνω όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Εκτελεί το άνω όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίβλημα (border-box) |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίβλημα (border-box) |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογικό ομαδοποίηση) που χρησιμοποιείται για την ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης παρουσίας μαθηματικού κειμένου. Ένα αντικείμενο σε κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί ώστε να μη επιτρέπει αλλαγές γραμμής εντός. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κάθετη διάταξη |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Τοποθετεί μια γραμμή στο κάτω μέρος του στοιχείου |

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
* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
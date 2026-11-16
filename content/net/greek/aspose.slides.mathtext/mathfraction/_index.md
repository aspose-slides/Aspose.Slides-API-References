---
title: MathFraction
second_title: Αναφορά API Aspose.Sildes για .NET
description: Καθορίζει το αντικείμενο κλάσματος που αποτελείται από έναν αριθμητή και έναν παρονομαστή χωρισμένους με μια γραμμή κλάσματος. Η γραμμή κλάσματος μπορεί να είναι οριζόντια ή διαγώνια ανάλογα με τις ιδιότητες του κλάσματος. Το αντικείμενο κλάσματος χρησιμοποιείται επίσης για την αναπαράσταση της συνάρτησης στοίβας που τοποθετεί ένα στοιχείο πάνω από άλλο χωρίς γραμμή κλάσματος.
type: docs
weight: 8710
url: /el/aspose.slides.mathtext/mathfraction/
---
## MathFraction κλάση

Καθορίζει το αντικείμενο κλάσματος, που αποτελείται από έναν αριθμητή και έναν παρονομαστή χωρισμένους με μια γραμμή κλάσματος. Η γραμμή κλάσματος μπορεί να είναι οριζόντια ή διαγώνια, ανάλογα με τις ιδιότητες του κλάσματος. Το αντικείμενο κλάσματος χρησιμοποιείται επίσης για την αναπαράσταση της συνάρτησης στοίβας, η οποία τοποθετεί ένα στοιχείο πάνω από ένα άλλο, χωρίς γραμμή κλάσματος.

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | Αρχικοποιεί ένα MathFraction τύπου 'Bar' με τον καθορισμένο αριθμητή και παρονομαστή |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | Αρχικοποιεί το MathFraction με τον καθορισμένο αριθμητή, παρονομαστή και τύπο |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | Παρονομαστής |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | Τύπος κλάσματος, Προεπιλογή: Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | Αριθμητής |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Θέτει ένα σημάδι προφοράς (έναν χαρακτήρα πάνω σε αυτό το στοιχείο) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Πιάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Πιάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Πιάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Πιάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Πιάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Τοποθετεί ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Πιάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Πιάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | Λαμβάνει τα θυγατρικά στοιχεία |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια καμπύλη αγκύλη στο κάτω μέρος |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως η κάτω καμπύλη αγκύλη ή άλλον |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Πιάνει το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Πιάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Πιάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Πιάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Πιάνει το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Συνεδύνει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Συνεδύνει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Τοποθετεί μια γραμμή στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Πιάνει το κάτω όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Πιάνει το κάτω όριο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί κάτω δείκτη |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί κάτω δείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί κάτω και πάνω δείκτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί κάτω και πάνω δείκτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί κάτω και πάνω δείκτη στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί κάτω και πάνω δείκτη στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί πάνω δείκτη |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί πάνω δείκτη |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Πιάνει το άνω όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Πιάνει το άνω όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης εμφάνισης μαθηματικού κειμένου. Ένα αντικείμενο σε κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να εξυπηρετήσει ως σημείο διακοπής γραμμής, ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπει διακοπές γραμμής εντός. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κατακόρυφη διάταξη |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Τοποθετεί μια γραμμή στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

```csharp
[C#]
MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διεπαφή [IMathFraction](../imathfraction)
* χώρος ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συλλογή [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
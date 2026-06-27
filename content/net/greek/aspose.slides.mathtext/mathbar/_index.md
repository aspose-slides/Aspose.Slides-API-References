---
title: MathBar
second_title: Aspose.Sildes για .NET API Αναφορά
description: Καθορίζει τη λειτουργία μπαρ που αποτελείται από ένα βασικό όρισμα και μια άνω ή κάτω μπαρ
type: docs
weight: 8550
url: /el/aspose.slides.mathtext/mathbar/
---
## MathBar κλάση

Καθορίζει τη λειτουργία μπαρ, που αποτελείται από ένα βασικό όρισμα και μια άνω ή κάτω μπαρ

```csharp
public sealed class MathBar : MathElementBase, IMathBar
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathBar](mathbar#constructor)(IMathElement) | Αρχικοποιεί το MathBar με άνω μπαρ (Θέση Επάνω) |
| [MathBar](mathbar#constructor_1)(IMathElement, MathTopBotPositions) | Αρχικοποιεί το MathBar με την καθορισμένη θέση |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathbar/base) { get; } | Βασικό όρισμα |
| [Position](../../aspose.slides.mathtext/mathbar/position) { get; set; } | Θέση της γραμμής μπάρας. Προεπιλογή: Επάνω |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σημάδι τονισμού (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την περίπτωση ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την περίπτωση ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την περίπτωση ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την περίπτωση ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την περίπτωση ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως περιτύλιγμα |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την περίπτωση ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την περίπτωση ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathbar/getchildren)() | Λαμβάνει τα στοιχεία-παιδιά |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί το στοιχείο αυτό σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί το στοιχείο αυτό σε ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης, όπως η κάτω αγκύλη ή άλλος |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Λαμβάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Λαμβάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Λαμβάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Λαμβάνει το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Ενώνει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Ενώνει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Θέτει μια γραμμή στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί το στοιχείο αυτό σε πλαίσιο-περίγραμμα |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί το στοιχείο αυτό σε πλαίσιο-περίγραμμα |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για την ομαδοποίηση των στοιχείων μιας εξίσωσης ή άλλης παρουσίας μαθηματικού κειμένου. Ένα κουτιοποιημένο αντικείμενο μπορεί (π.χ.) να λειτουργεί ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργεί ως σημείο διακοπής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπονται διακοπές γραμμής εντός του. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κατακόρυφη σειρά |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Θέτει μια γραμμή στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
MathBar mathBar = new MathBar(new MathematicalText("x"));
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διεπαφή [IMathBar](../imathbar)
* χώρος ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
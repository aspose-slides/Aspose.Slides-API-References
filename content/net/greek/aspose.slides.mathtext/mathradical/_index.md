---
title: MathRadical
second_title: Aspose.Sildes για .NET API Αναφορά
description: Καθορίζει τη λειτουργία ρίζας που αποτελείται από μια βάση και έναν προαιρετικό εκθέτη. Παράδειγμα αντικειμένου ρίζας είναι .
type: docs
weight: 8960
url: /el/aspose.slides.mathtext/mathradical/
---
## MathRadical κλάση

Καθορίζει τη λειτουργία ρίζας, που αποτελείται από βάση και προαιρετικό εκθέτη. Παράδειγμα αντικειμένου ρίζας είναι √𝑥.

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | Αρχικοποιεί μια νέα παρουσία της MathRadical κλάσης. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | Όρισμα βάσης |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | Όρισμα εκθέτη |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | Απόκρυψη εκθέτη. Όταν είναι true, ο εκθέτης δεν εμφανίζεται, όπως στο √𝑥 |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σημάδι τόνου (έναν χαρακτήρα πάνω από αυτό το στοιχείο) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα και καθορισμένο επιπλέον όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα και καθορισμένο επιπλέον όρισμα |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τυλίγει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Τυλίγει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες πλαισίου |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Χρησιμοποιεί μια συνάρτηση ενός ορίσματος με αυτή την παρουσία ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Χρησιμοποιεί μια συνάρτηση ενός ορίσματος με αυτή την παρουσία ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | Λαμβάνει τα θυγατρικά στοιχεία |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω άγκυρα |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης, όπως κάτω άγκυρα ή άλλον |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Παίρνει το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Παίρνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Παίρνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Παίρνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Παίρνει το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Ενώνει ένα μαθηματικό στοιχείο και σχηματίζει ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Ενώνει ένα μαθηματικό κείμενο και σχηματίζει ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-αριό τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-αριό τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ορίζει μπάρα πάνω από αυτό το στοιχείο |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δοθέντος εκθέτη από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δοθέντος εκθέτη από το καθορισμένο όρισμα. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Παίρνει το κατώτερο όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Παίρνει το κατώτερο όριο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί δείκτη |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί δείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί εκθέτη |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί εκθέτη |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Παίρνει το ανώτερο όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Παίρνει το ανώτερο όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου τμήματος μαθηματικού κειμένου. Ένα κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχευσης, να χρησιμεύσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπεται αλλαγή γραμμής εντός. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κατακόρυφη σειρά |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ορίζει μπάρα στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διεπαφή [IMathRadical](../imathradical)
* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
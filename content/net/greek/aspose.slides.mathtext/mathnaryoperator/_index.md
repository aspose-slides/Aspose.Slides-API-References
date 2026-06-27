---
title: MathNaryOperator
second_title: Aspose.Sildes για .NET Αναφορά API
description: Καθορίζει ένα N-ary μαθηματικό αντικείμενο όπως Άθροισμα και Ολοκλήρωμα. Αποτελείται από έναν τελεστή, μια βάση ή τελεστέο και προαιρετικά άνω και κάτω όρια. Παραδείγματα N-ary τελεστών είναι Άθροισμα, Ένωση, Τομή, Ολοκλήρωμα
type: docs
weight: 8850
url: /el/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator κλάση

Προσδιορίζει ένα N-ary μαθηματικό αντικείμενο, όπως το Άθροισμα και το Ολοκλήρωμα. Αποτελείται από έναν τελεστή, μια βάση (ή τελεστέο), και προαιρετικά άνω και κάτω όρια. Παραδείγματα N-ary τελεστών είναι: Άθροισμα, Ένωση, Τομή, Ολοκλήρωμα

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## Κατασκευαστές

| Name | Description |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathNaryOperator. |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathNaryOperator. |

## Ιδιότητες

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | Βασικό όρισμα |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | Ο χαρακτήρας του τελεστή μεγαλώνει κάθετα ώστε να ταιριάζει με το ύψος του τελεστέου |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | Απόκρυψη δείκτη |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | Απόκρυψη εκθέτη |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | Η θέση των ορίων (δείκτης και εκθέτης) |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Χαρακτήρας Nary τελεστή π.χ.: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | Καθορίζει ένα επιχείρημα δείκτη που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το κάτω όριο |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | Καθορίζει ένα επιχείρημα εκθέτη που, για παράδειγμα, στην περίπτωση ενός ολοκληρώματος, ορίζει το άνω όριο |

## Μέθοδοι

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σημείο τονισμού (χαρακτήρας στην κορυφή αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Αποδέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την instance ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Αποδέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την instance ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Αποδέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την instance ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Αποδέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την instance ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Αποδέχεται τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την instance ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τοποθετεί ένα μαθηματικό στοιχείο μέσα σε παρενθέσεις |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Τοποθετεί ένα μαθηματικό στοιχείο μέσα σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Αποδέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την instance ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Αποδέχεται μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την instance ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | Παίρνει τα θυγατρικά στοιχεία |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή άλλον |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Αποδέχεται το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Αποδέχεται το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Αποδέχεται το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Αποδέχεται το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Αποδέχεται το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Σαν

δέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Σαν

δέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ορίζει μπάρα στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Αποδέχεται το χαμηλότερο όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Αποδέχεται το χαμηλότερο όριο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί δείκτη |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί δείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί εκθέτη |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί εκθέτη |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Αποδέχεται το άνω όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Αποδέχεται το άνω όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε κουτί-περίγραμμα |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε κουτί-περίγραμμα |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση συστατικών μιας εξίσωσης ή άλλου μαθηματικού κειμένου. Ένα τέτοιο κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργήσει ως σημείο διακοπής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπει αλλαγές γραμμής εντός. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κατακόρυφο σύνολο |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ορίζει μπάρα στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Example:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διασύνδεση [IMathNaryOperator](../imathnaryoperator)
* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
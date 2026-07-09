---
title: IMathElement
second_title: Aspose.Sildes για .NET API Αναφορά
description: Βασική διασύνδεση οποιουδήποτε μαθηματικού στοιχείου: κλάσμα, μαθηματικό κείμενο, συνάρτηση, έκφραση με πολλαπλά στοιχεία κλπ
type: docs
weight: 8230
url: /el/aspose.slides.mathtext/imathelement/
---
## IMathElement διασύνδεση

Βασική διασύνδεση οποιουδήποτε μαθηματικού στοιχείου: κλάσμα, μαθηματικό κείμενο, συνάρτηση, έκφραση με πολλαπλά στοιχεία κλπ

```csharp
public interface IMathElement
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Ορίζει ένα σημάδι τόνου (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο επιπλέον όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο επιπλέον όρισμα |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Τυλίγει αυτό το στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες πλαισίου |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Εκτελεί μια συνάρτηση με όρισμα χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Εκτελεί μια συνάρτηση με όρισμα χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Λαμβάνει τα παιδικά στοιχεία |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια καμπύλη αγκύλη στο κάτω μέρος |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης, όπως η κατώτερη καμπύλη αγκύλη ή άλλον |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Εκτελεί το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Εκτελεί το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Εκτελεί το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Εκτελεί το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Εκτελεί το ολοκλήρωμα |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-αριθμητικό τελεστή |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-αριθμητικό τελεστή |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Τοποθετεί μια μπάρα στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Λαμβάνει το κάτω όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Λαμβάνει το κάτω όριο |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Δημιουργεί δείκτη |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Δημιουργεί δείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Δημιουργεί εκθέτη |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Δημιουργεί εκθέτη |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Λαμβάνει το άνω όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Λαμβάνει το άνω όριο |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό πλαίσιο (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση των στοιχείων μιας εξίσωσης ή άλλου μαθηματικού κειμένου. Ένα αντικείμενο σε πλαίσιο μπορεί (π.χ.) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπεται αλλαγή γραμμής εντός του. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Τοποθετεί σε κάθετη διάταξη |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Τοποθετεί μια μπάρα στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* σύστημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
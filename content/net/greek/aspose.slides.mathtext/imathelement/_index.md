---
title: IMathElement
second_title: Aspose.Sildes για .NET Αναφορά API
description: Βασική διασύνδεση οποιουδήποτε μαθηματικού στοιχείου, όπως κλάσμα, μαθηματικό κείμενο, συνάρτηση, έκφραση με πολλαπλά στοιχεία κ.λπ.
type: docs
weight: 8210
url: /el/aspose.slides.mathtext/imathelement/
---
## IMathElement διασύνδεση

Βασική διασύνδεση οποιουδήποτε μαθηματικού στοιχείου: κλάσμα, μαθηματικό κείμενο, συνάρτηση, έκφραση με πολλά στοιχεία κ.λπ.

```csharp
public interface IMathElement
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Ορίζει ένα σημάδι τονισμού (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Παίρνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Παίρνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Παίρνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Παίρνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα και καθορισμένο επιπλέον όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Παίρνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την παρουσία ως όρισμα και καθορισμένο επιπλέον όρισμα |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Τοποθετεί αυτό το στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως περιγράμματα |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την παρουσία ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την παρουσία ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Λαμβάνει τα παιδικά στοιχεία |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης, όπως η κάτω αγκύλη ή άλλος |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Παίρνει το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Παίρνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Παίρνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Παίρνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Παίρνει το ολοκλήρωμα |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-αριθμητικό τελεστή |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-αριθμητικό τελεστή |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Τοποθετεί μια γραμμή στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Παίρνει το κάτω όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Παίρνει το κάτω όριο |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Δημιουργεί υποδείκτη |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Δημιουργεί υποδείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί υποδείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Δημιουργεί υποδείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί υποδείκτη και εκθέτη στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Δημιουργεί υποδείκτη και εκθέτη στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Δημιουργεί εκθέτη |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Δημιουργεί εκθέτη |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Παίρνει το άνω όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Παίρνει το άνω όριο |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για την ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου μαθηματικού κειμένου. Ένα κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργήσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπονται αλλαγές γραμμής μέσα σε αυτό. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Τοποθετεί σε κατακόρυφο πίνακα |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Τοποθετεί μια γραμμή στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Δείτε επίσης

* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
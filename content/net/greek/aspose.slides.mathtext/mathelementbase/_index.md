---
title: MathElementBase
second_title: Aspose.Sildes για .NET Αναφορά API
description: Βασική κλάση για IMathElement με την υλοποίηση κάποιων μεθόδων που είναι κοινές σε όλες τις κληρονόμενες κλάσεις. Μόνο για εσωτερική χρήση. Η κληρονόμενη κλάση πρέπει να είναι IMathElement.
type: docs
weight: 8680
url: /el/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase κλάση

Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be IMathElement.

```csharp
public abstract class MathElementBase : IMathElement
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σημείο τόνου (χαρακτήρας στο επάνω μέρος αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | Εκτελεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Εκτελεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | Εκτελεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Εκτελεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Εκτελεί την καθορισμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | Εκτελεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα της συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | Εκτελεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα της συνάρτησης |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας άγκιστρο στο κάτω μέρος |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης, όπως άγκιστρο κάτω ή άλλον |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | Υπολογίζει το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Υπολογίζει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | Υπολογίζει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Υπολογίζει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Υπολογίζει το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Τοποθετεί μια γραμμή στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | Λαμβάνει το κάτω όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | Λαμβάνει το κάτω όριο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | Δημιουργεί υποδείκτη |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | Δημιουργεί υποδείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί υποδείκτη και υπέρδεικτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Δημιουργεί υποδείκτη και υπέρδεικτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί υποδείκτη και υπέρδεικτη στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Δημιουργεί υποδείκτη και υπέρδεικτη στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | Δημιουργεί υπέρδεικτη |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | Δημιουργεί υπέρδεικτη |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | Λαμβάνει το άνω όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | Λαμβάνει το άνω όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης εμφάνισης μαθηματικού κειμένου. Ένα στοιχείο σε κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να λειτουργήσει ως σημείο διακοπής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπεται διάσπαση γραμμής εντός του. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κατακόρυφη σειρά |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Τοποθετεί μια γραμμή στο κάτω μέρος αυτού του στοιχείου |

### Δείτε επίσης

* διασύνδεση [IMathElement](../imathelement)
* χώρος ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
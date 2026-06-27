---
title: MathLimit
second_title: Aspose.Sildes για .NET API Αναφορά
description: Καθορίζει το αντικείμενο Limit που αποτελείται από κείμενο στην γραμμή βάσης και κείμενο μειωμένου μεγέθους αμέσως πάνω ή κάτω από αυτό.
type: docs
weight: 8800
url: /el/aspose.slides.mathtext/mathlimit/
---
## MathLimit κλάση

Specifies the Limit object, consisting of text on the baseline and reduced-size text immediately above or below it.

```csharp
public sealed class MathLimit : MathElementBase, IMathLimit
```

## Κατασκευαστές

| Name | Description |
| --- | --- |
| [MathLimit](mathlimit#constructor)(IMathElement, IMathElement) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathLimit με το χαμηλότερο όριο |
| [MathLimit](mathlimit#constructor_1)(IMathElement, IMathElement, bool) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathLimit. |

## Ιδιότητες

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathlimit/base) { get; } | Βασικό όρισμα |
| [Limit](../../aspose.slides.mathtext/mathlimit/limit) { get; } | Όρισμα ορίου |
| [UpperLimit](../../aspose.slides.mathtext/mathlimit/upperlimit) { get; set; } | Καθορίζει το άνω ή το κάτω όριο |

## Μέθοδοι

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα διακριτικό (χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τυλίγει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Τυλίγει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathlimit/getchildren)() | Λαμβάνει τα στοιχεία-παιδιά |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας κάτω αγκύλη |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή άλλος |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Λαμβάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Λαμβάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Λαμβάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Λαμβάνει το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-αρικό τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-αρικό τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Θέτει μπάρα πάνω από αυτό το στοιχείο |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δοθέντος βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δοθέντος βαθμού από το καθορισμένο όρισμα. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Λαμβάνει το κάτω όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Λαμβάνει το κάτω όριο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί δείκτη |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί δείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί εκθέτη |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί εκθέτη |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Λαμβάνει το άνω όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Λαμβάνει το άνω όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίγραμμα |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για την ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου μαθηματικού κειμένου. Ένα πλαίσια αντικειμένου μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργήσει ως σημείο διακοπής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπεται η διακοπή γραμμής εντός του. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κάθετο πίνακα |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Θέτει μπάρα στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("𝑛→∞"));
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διεπαφή [IMathLimit](../imathlimit)
* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
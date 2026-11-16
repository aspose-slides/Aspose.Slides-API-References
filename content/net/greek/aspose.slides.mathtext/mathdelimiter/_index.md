---
title: MathDelimiter
second_title: Aspose.Sildes για .NET Αναφορά API
description: Καθορίζει το αντικείμενο διαχωριστικού που αποτελείται από χαρακτήρες ανοίγματος και κλεισίματος, όπως παρενθέσεις, άγκυλες, αγκύλες και κατακόρυφες γραμμές, και ένα ή περισσότερα μαθηματικά στοιχεία μέσα, χωρισμένα με καθορισμένο χαρακτήρα. Παραδείγματα 2 2x7C2
type: docs
weight: 8670
url: /el/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter κλάση

Καθορίζει το αντικείμενο διαχωριστικού, που αποτελείται από χαρακτήρες έναρξης και λήξης (όπως παρενθέσεις, άγκιστρα, αγκύλες και κάθετες γραμμές) και ένα ή περισσότερα μαθηματικά στοιχεία μέσα, χωρισμένα με έναν καθορισμένο χαρακτήρα. Παραδείγματα: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Αρχικοποιεί το MathDelimiter με το καθορισμένο στοιχείο ως μοναδικό βασικό επιχείρημα |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Ένα ή περισσότερα μαθηματικά στοιχεία διαχωρισμένα από χαρακτήρες διαχωριστικού |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Το Delimiter Beginning Character καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα διαχωριστικού. Τα μαθηματικά διαχωριστικά είναι χαρακτήρες περιβλήματος όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλογή: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Καθορίζει το σχήμα των διαχωριστικών στο αντικείμενο διαχωριστικού. Όταν είναι MathDelimiterShape.Centered, τα διαχωριστικά κεντρώνονται γύρω από τον άξονα των μαθηματικών του κειμένου και προσαρμόζονται ώστε να ταιριάζουν στο πλήρες ύψος του περιεχομένου τους. Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Το Delimiter Ending Character καθορίζει τον τελικό, ή κλειστό, χαρακτήρα διαχωριστικού. Τα μαθηματικά διαχωριστικά είναι χαρακτήρες περιβλήματος όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλογή: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Καθορίζει την αύξηση των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, τα διαχωριστικά μεγαλώνουν κάθετα ώστε να ταιριάζουν με το ύψος του τελεστή τους. Η προεπιλεγμένη τιμή είναι true. |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Το Delimiter Separator Character καθορίζει τον χαρακτήρα που χωρίζει τα επιχειρήματα στο αντικείμενο διαχωριστικού. Η προεπιλογή: '&#x7C;'. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Θέτει ένα σημείο τονισμού (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Εκτελεί την καθορισμένη λειτουργία χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Εκτελεί την καθορισμένη λειτουργία χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Εκτελεί την καθορισμένη λειτουργία χρησιμοποιώντας αυτό το αντικείμενο ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Εκτελεί την καθορισμένη λειτουργία χρησιμοποιώντας αυτό το αντικείμενο ως πρώτο όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Εκτελεί την καθορισμένη λειτουργία χρησιμοποιώντας αυτό το αντικείμενο ως πρώτο όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Διαχωρίζει τα επιχειρήματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα διαχωριστικού |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Τοποθετεί ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Εκτελεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Εκτελεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτό το αντικείμενο ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Παίρνει τα παιδικά στοιχεία |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή άλλον |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Υπολογίζει το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Υπολογίζει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Υπολογίζει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Υπολογίζει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Υπολογίζει το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Ενώνει ένα μαθηματικό στοιχείο και σχηματίζει ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Ενώνει ένα μαθηματικό κείμενο και σχηματίζει ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Θέτει μια γραμμή στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Λαμβάνει το κατώτερο όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Λαμβάνει το κατώτερο όριο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί δείκτη |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί δείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί δείκτη και εκθέτη δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί εκθέτη |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί εκθέτη |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Λαμβάνει το ανώτερο όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Λαμβάνει το ανώτερο όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίβλημα |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περίβλημα |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό πλαίσιο (λογική ομαδοποίηση) που χρησιμοποιείται για να ομαδοποιήσει στοιχεία μιας εξίσωσης ή άλλου στιγμιότυπου μαθηματικού κειμένου. Ένα αντικείμενο σε πλαίσιο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργεί ως σημείο αλλαγής γραμμής, ή να ομαδοποιείται ώστε να μην επιτρέπει αλλαγές γραμμής εντός. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κατακόρυφη διάταξη |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Θέτει μια γραμμή στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διεπαφή [IMathDelimiter](../imathdelimiter)
* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
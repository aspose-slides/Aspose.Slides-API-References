---
title: MathDelimiter
second_title: Aspose.Sildes για .NET API Αναφορά
description: Καθορίζει το αντικείμενο οριοθέτη που αποτελείται από χαρακτήρες ανοίγματος και κλεισίματος όπως παρενθέσεις, αγκύλες, αγκύλες και κατακόρυφα σύμβολα και ένα ή περισσότερα μαθηματικά στοιχεία μέσα που χωρίζονται με έναν καθορισμένο χαρακτήρα. Παραδείγματα 2 2x7C2
type: docs
weight: 8630
url: /el/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter κλάση

Καθορίζει το αντικείμενο οριοθέτη, που αποτελείται από χαρακτήρες ανοίγματος και κλεισίματος (όπως παρενθέσεις, αγκύλες, αγκύλες και κατακόρυφα σύμβολα), και ένα ή περισσότερα μαθηματικά στοιχεία μέσα, χωρισμένα από έναν καθορισμένο χαρακτήρα. Παραδείγματα: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Αρχικοποιεί το MathDelimiter με το καθορισμένο στοιχείο ως μοναδικό βασικό όρισμα |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα από χαρακτήρες οριοθέτη |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Ο χαρακτήρας έναρξης οριοθέτη καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιέλιξης όπως παρενθέσεις, αγκύλες και αγκύλες. Η προεπιλογή: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Καθορίζει το σχήμα των οριοθετών στο αντικείμενο οριοθέτη. Όταν είναι MathDelimiterShape.Centered, οι οριοθέτες είναι κεντραρισμένοι γύρω από τον άξονα των μαθηματικών κειμένων και εξακολουθούν να προσαρμόζονται ώστε να ταιριάζουν στο συνολικό ύψος των περιεχομένων τους. Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Ο χαρακτήρας λήξης οριοθέτη καθορίζει τον τελικό, ή κλειστό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιέλιξης όπως παρενθέσεις, αγκύλες και αγκύλες. Η προεπιλογή: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Καθορίζει την αύξηση των χαρακτήρων BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι οριοθέτες αυξάνονται κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. Η προεπιλογή είναι true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Ο χαρακτήρας διαχωριστικού οριοθέτη καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο οριοθέτη. Η προεπιλογή: '&#x7C;'. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σημείο έμφασης (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Λαμβάνει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Οριοθετεί τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα οριοθέτη |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Λαμβάνει μια συνάρτηση ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Λαμβάνει μια συνάρτηση ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Αποκτά τα παιδικά στοιχεία |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης όπως κάτω αγκύλη ή άλλο |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Λαμβάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Λαμβάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Λαμβάνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Λαμβάνει το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-αριακό τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-αριακό τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Τοποθετεί μπάρα στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα |
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
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Λαμβάνει το άνω όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Λαμβάνει το άνω όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό πλαίσιο (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου τμήματος μαθηματικού κειμένου. Ένα πλαίσιο αντικείμενο μπορεί (π.χ.) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπεται αλλαγή γραμμής εντός του |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κάθετη σειρά |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Τοποθετεί μπάρα στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διεπαφή [IMathDelimiter](../imathdelimiter)
* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συστοιχία [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
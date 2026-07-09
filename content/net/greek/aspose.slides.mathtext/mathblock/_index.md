---
title: MathBlock
second_title: Aspose.Sildes για .NET API Αναφορά
description: Καθορίζει ένα στιγμιότυπο μαθηματικού κειμένου που περιέχεται σε ένα MathParagraph και ξεκινά σε νέα γραμμή. Όλες οι μαθηματικές ζώνες, συμπεριλαμβανομένων εξισώσεων, εκφράσεων, σειρών εξισώσεων ή εκφράσεων και τύπων, αντιπροσωπεύονται από math block.
type: docs
weight: 8590
url: /el/aspose.slides.mathtext/mathblock/
---
## MathBlock κλάση

Καθορίζει ένα στιγμιότυπο μαθηματικού κειμένου που περιλαμβάνεται σε ένα MathParagraph και ξεκινά σε νέα γραμμή. Όλες οι μαθηματικές ζώνες, συμπεριλαμβανομένων των εξισώσεων, εκφράσεων, πινάκων εξισώσεων ή εκφράσεων, και των τύπων, αντιπροσωπεύονται από math block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Δημιουργεί ένα νέο μαθηματικό μπλοκ και τοποθετεί τα καθορισμένα στοιχεία σε αυτό |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Δημιουργεί ένα νέο μαθηματικό μπλοκ και τοποθετεί το καθορισμένο στοιχείο σε αυτό |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Επιστρέφει τον αριθμό των παιδικών μαθηματικών στοιχείων που περιέχονται στην συλλογή. Μόνο για ανάγνωση Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Επιστρέφει false επειδή η συλλογή στοιχείων-παιδιών μπορεί να τροποποιηθεί. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Επιστρέφει ή ορίζει το IMathElement στο καθορισμένο ευρετήριο. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σημείο τονισμού (ένα χαρακτήρα στην κορυφή αυτού του στοιχείου) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Προσθέτει ένα μαθηματικό στοιχείο στο τέλος της συλλογής. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Εκτελεί τη καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Εκτελεί τη καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Εκτελεί τη καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Εκτελεί τη καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Εκτελεί τη καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Καθορίζει εάν η συλλογή περιέχει συγκεκριμένη τιμή. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Αντιγράφει σε καθορισμένο πίνακα. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Οριοθετεί τα παιδικά στοιχεία με χαρακτήρα διαχωριστή (χωρίς τις αγκύλες) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τυλίγει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Τυλίγει τα παιδικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Τυλίγει τα παιδικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους ως πλαίσιο και οριοθετεί με χαρακτήρα διαχωριστή |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Εκτελεί λειτουργία ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα λειτουργίας |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Εκτελεί λειτουργία ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα λειτουργίας |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Παίρνει τα παιδικά στοιχεία |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας κάτω αγκύλη |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή άλλον |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Καθορίζει το ευρετήριο ενός συγκεκριμένου μαθηματικού στοιχείου στη συλλογή. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Εισάγει ένα MathElement στη συλλογή στο καθορισμένο ευρετήριο. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Υπολογίζει το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Υπολογίζει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Υπολογίζει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Υπολογίζει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Υπολογίζει το ολοκλήρωμα |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Συνδέει ένα μαθηματικό στοιχείο με αυτό το μαθηματικό μπλοκ |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Συνδέει ένα μαθηματικό κείμενο με αυτό το μαθηματικό μπλοκ |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Συνδέει άλλο μαθηματικό μπλοκ με αυτό |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Ορίζει γραμμή στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Αφαιρεί το στοιχείο στο καθορισμένο ευρετήριο της συλλογής. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Λαβάνει το κατώτερο όριο |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Λαβάνει το κατώτερο όριο |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί δείκτη |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί δείκτη |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί εκθέτη |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί εκθέτη |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Λαβάνει το ανώτερο όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Λαβάνει το ανώτερο όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη οπτικό πλαίσιο (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου στιγμιοτύπου μαθηματικού κειμένου. Ένα αντικείμενο σε πλαίσιο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να λειτουργήσει ως σημείο διακοπής γραμμής, ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπει διακοπές γραμμής εντός. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Τοποθετεί τα παιδικά στοιχεία σε κατακόρυφη σειρά |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Ορίζει γραμμή στο κάτω μέρος αυτού του στοιχείου |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Αποθηκεύει το περιεχόμενο αυτού του [`MathBlock`](../mathblock) ως MathML |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διεπαφή [IMathBlock](../imathblock)
* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
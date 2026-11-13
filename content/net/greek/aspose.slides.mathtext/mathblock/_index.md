---
title: MathBlock
second_title: Aspose.Sildes για .NET αναφορά API
description: Καθορίζει ένα στιγμιότυπο μαθηματικού κειμένου που περιέχεται μέσα σε ένα MathParagraph και ξεκινά σε ξεχωριστή γραμμή. Όλες οι μαθηματικές ζώνες, συμπεριλαμβανομένων των εξισώσεων, εκφράσεων, πινάκων εξισώσεων ή εκφράσεων και τύπων, αντιπροσωπεύονται από math block.
type: docs
weight: 8610
url: /el/aspose.slides.mathtext/mathblock/
---
## MathBlock κλάση

Καθορίζει ένα στιγμιότυπο μαθηματικού κειμένου που περιέχεται μέσα σε ένα MathParagraph και ξεκινά σε ξεχωριστή γραμμή. Όλες οι ζώνες μαθηματικών, συμπεριλαμβανομένων των εξισώσεων, εκφράσεων, πινάκων εξισώσεων ή εκφράσεων και τύπων, αντιπροσωπεύονται από μπλοκ μαθηματικών.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Δημιουργεί ένα νέο μαθηματικό μπλοκ και τοποθετεί τα καθορισμένα στοιχεία σε αυτό |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Δημιουργεί ένα νέο μαθηματικό μπλοκ και τοποθετεί το καθορισμένο στοιχείο σε αυτό |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Παίρνει τον αριθμό των θυγατρικών μαθηματικών στοιχείων που πραγματικά περιέχονται στη συλλογή. Μόνο για ανάγνωση Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Επιστρέφει false επειδή η συλλογή θυγατρικών στοιχείων μπορεί να τροποποιηθεί. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Παίρνει ή ορίζει το IMathElement στο συγκεκριμένο δείκτη. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σημάδι τονισμού (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Προσθέτει ένα μαθηματικό στοιχείο στο τέλος της συλλογής. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την instance ως όρισμα. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την instance ως όρισμα. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την instance ως όρισμα. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την instance ως όρισμα και το καθορισμένο πρόσθετο όρισμα. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την instance ως όρισμα και το καθορισμένο πρόσθετο όρισμα. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Καθορίζει αν η συλλογή περιέχει μια συγκεκριμένη τιμή. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Αντιγράφει σε καθορισμένο πίνακα. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Οριοθετεί τα θυγατρικά στοιχεία με χαρακτήρα διαχωριστή (χωρίς τις αγκύλες). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τυλίγει ένα μαθηματικό στοιχείο σε παρενθέσεις. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Τυλίγει τα θυγατρικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Τυλίγει τα θυγατρικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους, ως πλαίσιο και οριοθετεί με χαρακτήρα διαχωριστή. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Καθορίζει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την instance ως όνομα συνάρτησης. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Καθορίζει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την instance ως όνομα συνάρτησης. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Λαμβάνει τα θυγατρικά στοιχεία. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης, όπως κάτω αγκύλη ή άλλον. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Καθορίζει το δείκτη ενός συγκεκριμένου μαθηματικού στοιχείου στη συλλογή. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Εισάγει ένα MathElement στη συλλογή στο καθορισμένο δείκτη. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Υπολογίζει το ολοκλήρωμα χωρίς όρια. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Υπολογίζει το ολοκλήρωμα. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Υπολογίζει το ολοκλήρωμα. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Υπολογίζει το ολοκλήρωμα. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Υπολογίζει το ολοκλήρωμα. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Συνδέει ένα μαθηματικό στοιχείο με αυτό το μαθηματικό μπλοκ. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Συνδέει ένα μαθηματικό κείμενο με αυτό το μαθηματικό μπλοκ. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Συνδέει ένα άλλο μαθηματικό μπλοκ με αυτό. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Τοποθετεί μια γραμμή στην κορυφή αυτού του στοιχείου. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Ορίζει το κάτω όριο. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Ορίζει το κάτω όριο. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί δείκτη. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί δείκτη. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα αριστερά. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί δείκτη και εκθέτη στα αριστερά. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στα δεξιά. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί δείκτη και εκθέτη στα δεξιά. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί εκθέτη. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί εκθέτη. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Ορίζει το άνω όριο. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Ορίζει το άνω όριο. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-κουτί. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-κουτί. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση συστατικών μιας εξίσωσης ή άλλου στιγμιοτύπου μαθηματικού κειμένου. Ένα κουτισμένο αντικείμενο μπορεί (για παράδειγμα) να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί ώστε να μην επιτρέπει αλλαγές γραμμής μέσα του. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Τοποθετεί τα θυγατρικά στοιχεία σε κάθετη σειρά. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Τοποθετεί μια γραμμή στο κάτω μέρος αυτού του στοιχείου. |
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
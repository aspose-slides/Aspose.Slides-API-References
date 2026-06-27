---
title: MathBlock
second_title: Aspose.Sildes για .NET API Αναφορά
description: Καθορίζει μια παρουσία μαθηματικού κειμένου που περιέχεται σε MathParagraph και αρχίζει σε ξεχωριστή γραμμή. Όλες οι μαθηματικές ζώνες, συμπεριλαμβανομένων εξισώσεων, εκφράσεων, πινάκων εξισώσεων ή εκφράσεων και τύπων, αντιπροσωπεύονται από math block.
type: docs
weight: 8570
url: /el/aspose.slides.mathtext/mathblock/
---
## MathBlock κλάση

Καθορίζει μια παρουσία μαθηματικού κειμένου που περιέχεται μέσα σε ένα MathParagraph και αρχίζει σε ξεχωριστή γραμμή. Όλες οι μαθηματικές ζώνες, συμπεριλαμβανομένων εξισώσεων, εκφράσεων, πινάκων εξισώσεων ή εκφράσεων και τύπων, αντιπροσωπεύονται από math block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Δημιουργεί ένα νέο μαθηματικό block και τοποθετεί τα καθορισμένα στοιχεία σε αυτό |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Δημιουργεί ένα νέο μαθηματικό block και τοποθετεί το καθορισμένο στοιχείο σε αυτό |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Επιστρέφει τον αριθμό των θυγατρικών στοιχείων μαθηματικών που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Επιστρέφει false επειδή η συλλογή των θυγατρικών στοιχείων μπορεί να τροποποιηθεί. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Ανακτά ή ορίζει το IMathElement στο καθορισμένο δείκτη. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σύμβολο τονισμού (ένα χαρακτήρα πάνω από αυτό το στοιχείο) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Προσθέτει ένα στοιχείο μαθηματικού στην άκρη της συλλογής. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Αποδίδει τη συγκεκριμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Αποδίδει τη συγκεκριμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Αποδίδει τη συγκεκριμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Αποδίδει τη συγκεκριμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Αποδίδει τη συγκεκριμένη λειτουργία χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Καταργεί όλα τα στοιχεία από τη συλλογή. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Καθορίζει αν η συλλογή περιέχει μια συγκεκριμένη τιμή. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Αντιγράφει σε καθορισμένο πίνακα. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Διαχωρίζει τα θυγατρικά στοιχεία με χαρακτήρα διαχωριστή (χωρίς τις αγκύλες). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τοποθετεί ένα στοιχείο μαθηματικού σε παρένθεση. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Τυλίγει τα θυγατρικά στοιχεία αυτού του block σε καθορισμένους χαρακτήρες, όπως παρένθεση ή άλλους χαρακτήρες, ως περιτύλιγμα. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Τυλίγει τα θυγατρικά στοιχεία αυτού του block σε καθορισμένους χαρακτήρες, όπως παρένθεση ή άλλους, ως περιτύλιγμα και τα διαχωρίζει με χαρακτήρα διαχωριστή. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Αποδίδει μια λειτουργία ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα της λειτουργίας. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Αποδίδει μια λειτουργία ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα της λειτουργίας. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Ανακτά τα θυγατρικά στοιχεία. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μία κάτω αγκύλη. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης, όπως κάτω αγκύλη ή άλλο. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Καθορίζει το δείκτη ενός συγκεκριμένου μαθηματικού στοιχείου στη συλλογή. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Εισάγει ένα MathElement στη συλλογή στον καθορισμένο δείκτη. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Αποδίδει το ολοκλήρωμα χωρίς όρια. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Αποδίδει το ολοκλήρωμα. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Αποδίδει το ολοκλήρωμα. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Αποδίδει το ολοκλήρωμα. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Αποδίδει το ολοκλήρωμα. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Συνδέει ένα μαθηματικό στοιχείο με αυτό το μαθηματικό block. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Συνδέει ένα μαθηματικό κείμενο με αυτό το μαθηματικό block. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Συνδέει ένα άλλο μαθηματικό block με αυτό. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Θέτει μια γραμμή στην κορυφή αυτού του στοιχείου. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Αποδίδει το κατώτερο όριο. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Αποδίδει το κατώτερο όριο. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Δημιουργεί δείκτη. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Δημιουργεί δείκτη. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στο αριστερό μέρος. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Δημιουργεί δείκτη και εκθέτη στο αριστερό μέρος. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Δημιουργεί δείκτη και εκθέτη στο δεξιό μέρος. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Δημιουργεί δείκτη και εκθέτη στο δεξιό μέρος. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Δημιουργεί εκθέτη. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Δημιουργεί εκθέτη. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Αποδίδει το άνω όριο. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Αποδίδει το άνω όριο. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε κουτί-περίγραμμα. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε κουτί-περίγραμμα. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη οπτικό πλαίσιο (λογική ομαδοποίηση) που χρησιμοποιείται για την ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης παρουσίας μαθηματικού κειμένου. Ένα στοιχείο σε πλαίσιο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να χρησιμεύσει ως σημείο διακοπής γραμμής, ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπεται η αλλαγή γραμμής εντός του. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Τοποθετεί τα θυγατρικά στοιχεία σε κάθετη σειρά. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Θέτει μια γραμμή στο κάτω μέρος αυτού του στοιχείου. |
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
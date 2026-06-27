---
title: MathBox
second_title: Aspose.Sildes για το .NET API Αναφορά
description: Καθορίζει τη λογική συσκευασία (συσκείαση) μαθηματικού στοιχείου. Για παράδειγμα, ένα αντικείμενο σε κουτί μπορεί να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργήσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπονται αλλαγές γραμμής εντός. Για παράδειγμα, ο τελεστής πρέπει να τοποθετηθεί σε κουτί για να αποτραπούν οι αλλαγές γραμμής.
type: docs
weight: 8610
url: /el/aspose.slides.mathtext/mathbox/
---
## MathBox κλάση

Καθορίζει τη λογική περιβλήση (συσκείαση) μαθηματικού στοιχείου. Για παράδειγμα, ένα αντικείμενο σε κουτί μπορεί να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργήσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπονται αλλαγές γραμμής εντός του. Για παράδειγμα, ο τελεστής "==" πρέπει να τοποθετηθεί σε κουτί για να αποτρέπεται η αλλαγή γραμμής.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Αρχικοποιεί το MathBox με το καθορισμένο στοιχείο ως όρισμα |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Όταν είναι true, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. Προεπιλογή: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Βασικό όρισμα |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Διαφορικό Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., 𝑑𝑥 σε ολοκληρωτέο) και λαμβάνει το κατάλληλο οριζόντιο διάστιχο για το μαθηματικό διαφορικό. Προεπιλογή: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Ρητή διακοπή καθορίζει εάν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να αναδιπλώνεται στην αρχή του αντικειμένου. Καθορίζει τον αριθμό του τελεστή στην προηγούμενη γραμμή μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο ευθυγράμμισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255 Προεπιλογή: 0 (χωρίς ρητή διακοπή) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break Αυτή η ιδιότητα καθορίζει την ιδιότητα «αδιάσπαστο» του αντικειμένου box. Όταν είναι true, δεν μπορούν να συμβούν αλλαγές γραμμής εντός του κουτιού. Αυτό μπορεί να είναι σημαντικό για εξομοιωτές τελεστών που αποτελούνται από περισσότερους από έναν δυαδικό τελεστή. Όταν αυτό το στοιχείο δεν καθοριστεί, επιτρέπονται αλλαγές γραμμής μέσα στο κουτί. Προεπιλογή: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. Όταν είναι true, το κουτί και το περιεχόμενό του συμπεριφέρονται ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να λειτουργήσει ως σημείο αλλαγής γραμμής και να ευθυγραμμιστεί με άλλους τελεστές. Τα Operator Emulator χρησιμοποιούνται συχνά όταν ένα ή περισσότερα σύμβολα συνδυάζονται για να formen έναν τελεστή, όπως το '=='. Προεπιλογή: false |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σημάδι τονισμού (έναν χαρακτήρα πάνω από αυτό το στοιχείο) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Εκτελεί τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτό το αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί ένα κλάσμα με αυτό το αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτό το αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτό το αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Εκτελεί μια συνάρτηση με ένα όρισμα χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Εκτελεί μια συνάρτηση με ένα όρισμα χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Λαμβάνει τα παιδικά στοιχεία |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης, όπως κάτω αγκύλη ή άλλο |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Εκτελεί το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Εκτελεί το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Εκτελεί το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Εκτελεί το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Εκτελεί το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Τοποθετεί μια μπάρα στην κορυφή αυτού του στοιχείου |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
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
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Λαμβάνει το ανώτερο όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Λαμβάνει το ανώτερο όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-κουτί |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε ένα πλαίσιο-κουτί |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε ένα μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση των στοιχείων μιας εξίσωσης ή άλλου δείγματος μαθηματικού κειμένου. Ένα αντικείμενο σε κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργήσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπονται αλλαγές γραμμής εντός του. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κατακόρυφο σύνολο |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Τοποθετεί μια μπάρα στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Example:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διασύνδεση [IMathBox](../imathbox)
* χώρος ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
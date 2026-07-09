---
title: MathBox
second_title: Aspose.Sildes για .NET API Reference
description: Καθορίζει τη λογική συσκευασία (boxing) ενός μαθηματικού στοιχείου. Για παράδειγμα, ένα αντικείμενο σε κουτί μπορεί να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να λειτουργήσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπεται η αλλαγή γραμμής εντός. Για παράδειγμα, ο  τελεστής πρέπει να τοποθετηθεί σε κουτί για να αποτραπούν οι αλλαγές γραμμής.
type: docs
weight: 8630
url: /el/aspose.slides.mathtext/mathbox/
---
## MathBox κλάση

Καθορίζει τη λογική περιτύλιξη (συσκευασία) ενός μαθηματικού στοιχείου. Για παράδειγμα, ένα αντικείμενο σε κουτί μπορεί να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να λειτουργήσει ως σημείο αλλαγής γραμμής, ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπονται αλλαγές γραμμής εντός του. Για παράδειγμα, ο τελεστής "==" πρέπει να τοποθετηθεί σε κουτί για να αποτραπούν οι αλλαγές γραμμής.

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
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Όταν είναι true, αυτός ο προσομοιωτής τελεστή λειτουργεί ως σημείο στοίχισης· δηλαδή, τα καθορισμένα σημεία στοίχισης σε άλλες εξισώσεις μπορούν να στοιχιστούν με αυτό. Προεπιλογή: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Βασικό όρισμα |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Διαφορικός Όταν είναι true, το κουτί λειτουργεί ως διαφορικό (π.χ., 𝑑𝑥 σε ολοκληρωτέο) και λαμβάνει την κατάλληλη οριζόντια απόσταση για το μαθηματικό διαφορικό. Προεπιλογή: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Συγκεκριμένη διακοπή καθορίζει αν υπάρχει αλλαγή γραμμής στην αρχή του αντικειμένου Box, ώστε η γραμμή να τυλίγεται στην αρχή του αντικειμένου box. Καθορίζει τον αριθμό του τελεστή στην προηγούμενη γραμμή μαθηματικού κειμένου που θα χρησιμοποιηθεί ως σημείο στοίχισης για την τρέχουσα γραμμή μαθηματικού κειμένου. Πιθανές τιμές: 1..255. Προεπιλογή: 0 (χωρίς συγκεκριμένη διακοπή) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Χωρίς διακοπή Αυτή η ιδιότητα καθορίζει την ιδιότητα "αδιάσπαστο" στο αντικείμενο box. Όταν είναι true, δεν μπορούν να συμβούν αλλαγές γραμμής εντός του box. Αυτό μπορεί να είναι σημαντικό για προσομοιωτές τελεστή που αποτελούνται από περισσότερους από έναν δυαδικό τελεστή. Όταν αυτό το στοιχείο δεν καθορίζεται, οι αλλαγές μπορούν να συμβούν μέσα στο box. Προεπιλογή: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. Όταν είναι true, το κουτί και το περιεχόμενό του λειτουργούν ως ένας ενιαίος τελεστής και κληρονομούν τις ιδιότητες ενός τελεστή. Αυτό σημαίνει, για παράδειγμα, ότι ο χαρακτήρας μπορεί να λειτουργήσει ως σημείο αλλαγής γραμμής και μπορεί να στοιχιστεί με άλλους τελεστές. Οι προσομοιωτές τελεστή χρησιμοποιούνται συχνά όταν ένα ή περισσότερα σύμβολα συνδυάζονται για να σχηματίσουν έναν τελεστή, όπως '=='. Προεπιλεγμένη τιμή: false |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Ορίζει ένα σημάδι τονισμού (έναν χαρακτήρα πάνω από αυτό το στοιχείο) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Παίρνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Τοποθετεί ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαισίωση |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Λαμβάνει τα παιδικά στοιχεία |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας αγκύλη κάτω |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή άλλον |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Παίρνει το ολοκλήρωμα χωρίς όρια |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Παίρνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Παίρνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Παίρνει το ολοκλήρωμα |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Παίρνει το ολοκλήρωμα |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Ενώνει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Ενώνει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Δημιουργεί έναν N-ary τελεστή |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Δημιουργεί έναν N-ary τελεστή |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Τοποθετεί μια γραμμή στην κορυφή αυτού του στοιχείου |
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
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Λαμβάνει το άνω όριο |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Λαμβάνει το άνω όριο |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περιγράμματος |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περιγράμματος |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Τοποθετεί αυτό το στοιχείο σε μη οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση των στοιχείων μιας εξίσωσης ή άλλης εμφάνισης μαθηματικού κειμένου. Ένα αντικείμενο σε κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο στοίχισης, να λειτουργήσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί έτσι ώστε να μην επιτρέπεται η αλλαγή γραμμής εντός του. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Τοποθετεί σε κατακόρυφο πίνακα |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Τοποθετεί μια γραμμή στο κάτω μέρος αυτού του στοιχείου |

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Δείτε επίσης

* κλάση [MathElementBase](../mathelementbase)
* διεπαφή [IMathBox](../imathbox)
* χώρο ονομάτων [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
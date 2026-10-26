---
title: IParagraphFormat
second_title: Aspose.Sildes για την αναφορά API του .NET
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης παραγράφου. Σε αντίθεση με IParagraphFormatEffectiveData./iparagraphformateffectivedata όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 6590
url: /el/aspose.slides/iparagraphformat/
---
## IParagraphFormat διεπαφή

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης παραγράφου. Σε αντίθεση με [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

```csharp
public interface IParagraphFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Επιστρέφει ή ορίζει την ευθυγράμμιση κειμένου σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Επιστρέφει τη μορφή κουκίδας της παραγράφου. Μόνο για ανάγνωση [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Επιστρέφει την προεπιλεγμένη μορφή τμήματος μιας παραγράφου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Επιστρέφει ή ορίζει το βάθος της παραγράφου. Η τιμή 0 σημαίνει άγνωστη τιμή. Ανάγνωση/εγγραφή Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Καθορίζει εάν χρησιμοποιείται η αναίρεση γραμμής Ανατολικής Ασίας σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Επιστρέφει ή ορίζει την ευθυγράμμιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Καθορίζει εάν χρησιμοποιείται η κρεμαστή στίξη σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Επιστρέφει ή ορίζει την εσοχή πρώτης γραμμής/κρεμαστής εσοχής της παραγράφου χωρίς κληρονομικότητα. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Ανάγνωση/εγγραφή Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Καθορίζει εάν χρησιμοποιείται η αναίρεση γραμμής Λατινικά σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονομικότητα. Ανάγνωση/εγγραφή Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Καθορίζει εάν χρησιμοποιείται η γραφή Δεξιά προς Αριστερά σε μια παράγραφο. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Επιστρέφει ή ορίζει το ποσό του διαστήματος μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. Μια θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να έχει το λευκό διάστημα. Μια αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδα σημείων. Ανάγνωση/εγγραφή Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Επιστρέφει ή ορίζει το ποσό του διαστήματος πριν την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονομικότητα. Μια θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να έχει το λευκό διάστημα. Μια αρνητική τιμή καθορίζει το μέγεθος του λευκού διαστήματος σε μονάδα σημείων. Ανάγνωση/εγγραφή Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Επιστρέφει ή ορίζει το ποσό του διαστήματος μεταξύ των βασικών γραμμών σε μια παράγραφο. Θετική τιμή σημαίνει ποσοστό, αρνητική - μέγεθος σε σημεία. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Επιστρέφει τις εσοχές μιας παραγράφου. Δεν εφαρμόζεται κληρονομικότητα. Μόνο για ανάγνωση [`ITabCollection`](../itabcollection). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης παραγράφου με την εφαρμοσμένη κληρονομικότητα. |

### Σχόλια

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης παραγράφου που ορίζονται για τη συγκεκριμένη παράγραφο. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά τη λήψη των τιμών, έτσι στην πλειονότητα των περιπτώσεων θα λάβετε τιμές που σημαίνουν «απροσδιόριστο». Για να λάβετε τις αποτελεσματικές τιμές των παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [`GetEffective`](./geteffective) που επιστρέφει ένα [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Δείτε επίσης

* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
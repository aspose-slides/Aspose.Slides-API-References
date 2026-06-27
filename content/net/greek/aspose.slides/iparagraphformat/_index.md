---
title: IParagraphFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης παραγράφου. Σε αντίθεση με IParagraphFormatEffectiveData./iparagraphformateffectivedata όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.
type: docs
weight: 6570
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
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Επιστρέφει ή ορίζει τη στοίχιση κειμένου σε μια παράγραφο χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Επιστρέφει τη μορφή κουκκίδας της παραγράφου. Μόνο για ανάγνωση [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Επιστρέφει τη μορφή προεπιλεγμένου τμήματος μιας παραγράφου. Δεν εφαρμόζεται κληρονόμηση. Μόνο για ανάγνωση [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Επιστρέφει ή ορίζει το προεπιλεγμένο μέγεθος εσοχής χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Επιστρέφει ή ορίζει το βάθος της παραγράφου. Η τιμή 0 σημαίνει ακαθόριστη τιμή. Ανάγνωση/Εγγραφή Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Καθορίζει αν χρησιμοποιείται αλλαγή γραμμής Ανατολικής Ασίας σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Επιστρέφει ή ορίζει μια στοίχιση γραμματοσειράς σε μια παράγραφο χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Καθορίζει αν χρησιμοποιείται κρεμαστή στίξη σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Επιστρέφει ή ορίζει την πρώτη εσοχή/κρεμαστή εσοχή της παραγράφου χωρίς κληρονόμηση. Η κρεμαστή εσοχή μπορεί να οριστεί με αρνητικές τιμές. Ανάγνωση/Εγγραφή Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Καθορίζει αν χρησιμοποιείται αλλαγή γραμμής Λατινικού σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε μια παράγραφο χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Επιστρέφει ή ορίζει το δεξί περιθώριο σε μια παράγραφο χωρίς κληρονόμηση. Ανάγνωση/Εγγραφή Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Καθορίζει αν χρησιμοποιείται γράψιμο από δεξιά προς αριστερά σε μια παράγραφο. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/Εγγραφή [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Επιστρέφει ή ορίζει το ποσό του κενού μετά την τελευταία γραμμή σε μια παράγραφο χωρίς κληρονόμηση. Μία θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να έχει το κενό. Μία αρνητική τιμή καθορίζει το μέγεθος του κενού σε μονάδες σημείου. Ανάγνωση/Εγγραφή Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Επιστρέφει ή ορίζει το ποσό του κενού πριν από την πρώτη γραμμή σε μια παράγραφο χωρίς κληρονόμηση. Μία θετική τιμή καθορίζει το ποσοστό του μεγέθους γραμματοσειράς που πρέπει να έχει το κενό. Μία αρνητική τιμή καθορίζει το μέγεθος του κενού σε μονάδες σημείου. Ανάγνωση/Εγγραφή Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Επιστρέφει ή ορίζει το ποσό του κενού μεταξύ των βασικών γραμμών σε μια παράγραφο. Θετική τιμή σημαίνει ποσοστό, αρνητική - μέγεθος σε σημεία. Δεν εφαρμόζεται κληρονόμηση. Ανάγνωση/Εγγραφή Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Επιστρέφει τις εσοχές μιας παραγράφου. Δεν εφαρμόζεται κληρονόμηση. Μόνο για ανάγνωση [`ITabCollection`](../itabcollection). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Αποκτά τα αποτελεσματικά δεδομένα μορφοποίησης παραγράφου με την εφαρμοσμένη κληρονόμηση. |

### Σχόλια

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης παραγράφου που ορίζονται για τη συγκεκριμένη παράγραφο. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονόμηση κατά την ανάκτηση τιμών, έτσι ώστε στην πλειονότητα των περιπτώσεων θα λαμβάνετε τιμές που σημαίνουν "ακαθόριστο".

Για να λάβετε τις αποτελεσματικές τιμές παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [`GetEffective`](./geteffective) που επιστρέφει μια περίπτωση [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

## Δείτε επίσης

* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
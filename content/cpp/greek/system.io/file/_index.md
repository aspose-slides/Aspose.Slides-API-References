---
title: File
second_title: Αναφορά API του Aspose.Slides για C++
description: Παρέχει μεθόδους για τη διαχείριση αρχείων. Πρόκειται για στατικό τύπο χωρίς υπηρεσίες δημιουργίας παραδειγμάτων. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με κανέναν τρόπο.
type: docs
weight: 261
url: /el/system.io/file/
---
## File κλάση

Provides methods for manipulating files. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class File
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Προσθέτει συμβολοσειρές από τη συγκεκριμένη συλλογή συμβολοσειρών στο συγκεκριμένο αρχείο χρησιμοποιώντας την καθορισμένη κωδικοποίηση, γράφοντας κάθε συμβολοσειρά σε νέα γραμμή. Εάν το συγκεκριμένο αρχείο δεν υπάρχει, δημιουργείται. Το αρχείο κλείνει μετά την εγγραφή όλων των συμβολοσειρών. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Προσθέτει τη συγκεκριμένη συμβολοσειρά στο συγκεκριμένο αρχείο χρησιμοποιώντας την καθορισμένη κωδικοποίηση. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Δημιουργεί ένα αντικείμενο [StreamWriter](../streamwriter/) που προσθέτει κείμενο στο συγκεκριμένο αρχείο χρησιμοποιώντας κωδικοποίηση UTF-8. Εάν το συγκεκριμένο αρχείο δεν υπάρχει, δημιουργείται. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Αντιγράφει το συγκεκριμένο αρχείο στην καθορισμένη τοποθεσία. Εάν το αρχείο προορισμού υπάρχει ήδη, μια παράμετρος καθορίζει αν θα αντικατασταθεί. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Δημιουργεί ένα νέο αρχείο (ή αντικαθιστά το υπάρχον) και το ανοίγει για πρόσβαση ανάγνωσης και εγγραφής χρησιμοποιώντας το καθορισμένο μέγεθος buffer και τις επιλογές. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Δημιουργεί νέο ή ανοίγει υπάρχον αρχείο για εγγραφή κειμένου κωδικοποιημένου σε UTF-8. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Διαγράφει το συγκεκριμένο αρχείο ή κατάλογο. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Καθορίζει εάν η συγκεκριμένη διαδρομή αναφέρεται σε υπάρχον αρχείο. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Επιστρέφει τις ιδιότητες της συγκεκριμένης οντότητας. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Επιστρέφει την ημερομηνία δημιουργίας της συγκεκριμένης οντότητας σε τοπική ώρα. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Επιστρέφει την ημερομηνία δημιουργίας της συγκεκριμένης οντότητας σε ώρα UTC. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Επιστρέφει την ώρα τελευταίας πρόσβασης της συγκεκριμένης οντότητας σε τοπική ώρα. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Επιστρέφει την ώρα τελευταίας πρόσβασης της συγκεκριμένης οντότητας σε ώρα UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Επιστρέφει την ώρα τελευταίας εγγραφής της συγκεκριμένης οντότητας σε τοπική ώρα. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Επιστρέφει την ώρα τελευταίας εγγραφής της συγκεκριμένης οντότητας σε ώρα UTC. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Μετακινεί το συγκεκριμένο αρχείο στη νέα τοποθεσία. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Ανοίγει το συγκεκριμένο αρχείο στην καθορισμένη λειτουργία για ανάγνωση και εγγραφή χωρίς κοινή χρήση. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Ανοίγει το συγκεκριμένο αρχείο στην καθορισμένη λειτουργία, με τον καθορισμένο τύπο πρόσβασης και την επιλογή κοινής χρήσης. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Ανοίγει το συγκεκριμένο αρχείο μόνο για ανάγνωση, σε λειτουργία 'Open' με κοινή πρόσβαση για ανάγνωση. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Ανοίγει το υπάρχον συγκεκριμένο αρχείο για ανάγνωση κειμένου χρησιμοποιώντας κωδικοποίηση UTF-8 χωρίς κοινή χρήση. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Ανοίγει το συγκεκριμένο αρχείο μόνο για εγγραφή, σε λειτουργία 'OpenOrCreate' χωρίς κοινή χρήση. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Διαβάζει το περιεχόμενο του συγκεκριμένου δυαδικού αρχείου σε έναν πίνακα byte. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Διαβάζει το περιεχόμενο του συγκεκριμένου αρχείου κειμένου γραμμή-γραμμή σε έναν πίνακα συμβολοσειρών χρησιμοποιώντας την καθορισμένη κωδικοποίηση χαρακτήρων. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Διαβάζει το περιεχόμενο του συγκεκριμένου αρχείου κειμένου σε ένα μοναδικό αντικείμενο [String](../../system/string/) χρησιμοποιώντας την καθορισμένη κωδικοποίηση χαρακτήρων. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Διαβάζει το περιεχόμενο του συγκεκριμένου αρχείου κειμένου γραμμή-γραμμή χρησιμοποιώντας την καθορισμένη κωδικοποίηση χαρακτήρων και επιστρέφει μια συλλογή συμβολοσειρών που μπορεί να επαναληφθεί, όπου κάθε συμβολοσειρά αντιπροσωπεύει μια μοναδική γραμμή του περιεχομένου του αρχείου. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Αντικαθιστά το περιεχόμενο ενός αρχείου με ένα άλλο και δημιουργεί αντίγραφο ασφαλείας του αντικατεστημένου αρχείου. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Ορίζει τις καθορισμένες ιδιότητες στο συγκεκριμένο αρχείο. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ορίζει την ώρα τελευταίας εγγραφής της συγκεκριμένης οντότητας ως τοπική ώρα. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ορίζει την ώρα τελευταίας εγγραφής της συγκεκριμένης οντότητας ως ώρα UTC. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Αντικαθιστά το συγκεκριμένο δυαδικό αρχείο και γράφει τα καθορισμένα bytes σε αυτό. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Δημιουργεί ένα νέο αρχείο κειμένου ή αντικαθιστά το υπάρχον και γράφει όλες τις συμβολοσειρές από την καθορισμένη επαναληπτική συλλογή συμβολοσειρών σε αυτό, κάθε συμβολοσειρά σε νέα γραμμή, χρησιμοποιώντας την καθορισμένη κωδικοποίηση. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Δημιουργεί ένα νέο αρχείο κειμένου ή αντικαθιστά το υπάρχον και γράφει όλες τις συμβολοσειρές από τον καθορισμένο πίνακα συμβολοσειρών σε αυτό, κάθε συμβολοσειρά σε νέα γραμμή, χρησιμοποιώντας την καθορισμένη κωδικοποίηση. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Δημιουργεί ένα νέο αρχείο κειμένου ή αντικαθιστά το υπάρχον και γράφει το περιεχόμενο της συγκεκριμένης συμβολοσειράς σε αυτό χρησιμοποιώντας την καθορισμένη κωδικοποίηση. |

## Πεδία

| Field | Description |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Προεπιλεγμένη τιμή του αριθμού των bytes που γίνονται buffer κατά την ανάγνωση από και εγγραφή σε ένα αρχείο. |

## Δείτε επίσης

* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)
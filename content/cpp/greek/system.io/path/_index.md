---
title: Path
second_title: Aspose.Slides για C++ Αναφορά API
description: Παρέχει μεθόδους για τη διαχείριση διαδρομών. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιοτύπου. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα αυτού με κανένα τρόπο.
type: docs
weight: 339
url: /el/system.io/path/
---
## Κλάση Path

Παρέχει μεθόδους για τη διαχείριση διαδρομών. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιοτύπου. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα αυτού με κανένα τρόπο.

```cpp
class Path
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Αλλάζει την επέκταση στη συγκεκριμένη διαδρομή αρχείου. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Καθορίζει εάν η συγκεκριμένη διαδρομή είναι έγκυρη ελέγχοντας αν περιέχει μη έγκυρους χαρακτήρες. Εξαίρεση προβάλλεται εάν η διαδρομή περιέχει μη έγκυρους χαρακτήρες. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Συνδυάζει τα καθορισμένα τμήματα διαδρομής σε μία ενιαία διαδρομή, εισάγοντας χαρακτήρες διαχωρισμού καταλόγων μεταξύ των τμημάτων, εάν χρειάζεται. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Συνδυάζει δύο καθορισμένα τμήματα διαδρομής σε μία ενιαία διαδρομή, εισάγοντας χαρακτήρα διαχωρισμού καταλόγου μεταξύ των τμημάτων, εάν χρειάζεται. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Συνδυάζει τρία καθορισμένα τμήματα διαδρομής σε μία ενιαία διαδρομή, εισάγοντας χαρακτήρες διαχωρισμού καταλόγων μεταξύ των τμημάτων, εάν χρειάζεται. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Συνδυάζει τέσσερα καθορισμένα τμήματα διαδρομής σε μία ενιαία διαδρομή, εισάγοντας χαρακτήρες διαχωρισμού καταλόγων μεταξύ των τμημάτων, εάν χρειάζεται. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Επιστρέφει το όνομα του καταλόγου που αναφέρεται από τη συγκεκριμένη διαδρομή. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Επιστρέφει την επέκταση του αρχείου που αναφέρεται από τη συγκεκριμένη διαδρομή. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Επιστρέφει το όνομα του αρχείου που αναφέρεται από τη συγκεκριμένη διαδρομή. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Επιστρέφει το όνομα χωρίς επέκταση του αρχείου που αναφέρεται από τη συγκεκριμένη διαδρομή. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Μετατρέπει τη συγκεκριμένη διαδρομή σε απόλυτη διαδρομή. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Επιστρέφει έναν πίνακα που περιέχει χαρακτήρες που δεν επιτρέπονται στα ονόματα αρχείων. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Επιστρέφει έναν πίνακα που περιέχει χαρακτήρες που δεν επιτρέπονται στα ονόματα διαδρομών. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Επιστρέφει τον ριζικό κατάλογο της συγκεκριμένης διαδρομής. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Επιστρέφει ένα τυχαία δημιουργημένο όνομα αρχείου. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Δημιουργεί ένα νέο αρχείο με μοναδικό όνομα και επιστρέφει μια πλήρη διαδρομή προς αυτό. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Δημιουργεί ένα νέο αρχείο με μοναδικό όνομα και επιστρέφει μια πλήρη διαδρομή προς αυτό. Είναι συνώνυμη της μεθόδου [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Επιστρέφει τη διαδρομή του προσωρινού καταλόγου του τρέχοντος χρήστη. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Καθορίζει εάν η συγκεκριμένη διαδρομή αναφέρεται σε αρχείο με επέκταση. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Καθορίζει εάν η συγκεκριμένη διαδρομή περιέχει ρίζα. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Κανονικοποιεί τη συγκεκριμένη διαδρομή. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Επιστρέφει ένα στιγμιότυπο της κλάσης boost::filesystem::path που αντιπροσωπεύει τη συγκεκριμένη διαδρομή. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Επιστρέφει μια αναπαράσταση συμβολοσειράς του συγκεκριμένου αντικειμένου διαδρομής του Boost. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Ένας εναλλακτικός χαρακτήρας που χρησιμοποιείται για το διαχωρισμό επιπέδων καταλόγου σε μια διαδρομή. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Ένας χαρακτήρας που χρησιμοποιείται για το διαχωρισμό επιπέδων καταλόγου σε μια διαδρομή. |
| static [PathSeparator](./pathseparator/) | Ένας χαρακτήρας διαχωρισμού που χρησιμοποιείται για το διαχωρισμό συμβολοσειρών διαδρομής σε μεταβλητές περιβάλλοντος. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Ένας χαρακτήρας διαχωρισμού τόμου. |

## Παρατηρήσεις



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Δημιουργεί ένα τυχαίο όνομα αρχείου.
  auto filename = Path::GetRandomFileName();

  // Εκτυπώνει πληροφορίες για το όνομα του αρχείου.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Το παρακάτω παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
Όνομα αρχείου: qhuzkyqv.y6p
Όνομα αρχείου χωρίς επέκταση: qhuzkyqv
Επέκταση: .y6p
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)
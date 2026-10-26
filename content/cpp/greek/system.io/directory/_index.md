---
title: Directory
second_title: Αναφορά API του Aspose.Slides για C++
description: Περιέχει μεθόδους για τη διαχείριση καταλόγων. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμού. Δεν πρέπει ποτέ να δημιουργείτε παραδείγματα του με κανέναν τρόπο.
type: docs
weight: 235
url: /el/system.io/directory/
---
## Directory κλάση

Περιέχει μεθόδους για τη διαχείριση καταλόγων. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμού. Δεν πρέπει ποτέ να δημιουργείτε παραδείγματα του με κανέναν τρόπο.

```cpp
class Directory
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Δημιουργεί όλους τους καταλόγους στη καθορισμένη διαδρομή εάν δεν υπάρχουν. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Αφαιρεί το καθορισμένο αρχείο ή κατάλογο. Δεν προκαλεί εξαίρεση. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Αναζητά τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε όλο το δέντρο καταλόγων που έχει ρίζα στον καθορισμένο κατάλογο. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Αναζητά τα αρχεία που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε όλο το δέντρο καταλόγων που έχει ρίζα στον καθορισμένο κατάλογο. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Αναζητά τα αρχεία και τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε όλο το δέντρο καταλόγων που έχει ρίζα στον καθορισμένο κατάλογο. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Καθορίζει εάν η καθορισμένη διαδρομή αναφέρεται σε υπάρχον κατάλογο. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Επιστρέφει την ώρα δημιουργίας της καθορισμένης οντότητας ως τοπική ώρα. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Επιστρέφει την ώρα δημιουργίας της καθορισμένης οντότητας ως ώρα UTC. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Επιστρέφει το πλήρες όνομα (συμπεριλαμβανομένης της διαδρομής) του τρέχοντος καταλόγου. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Αναζητά τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε όλο το δέντρο καταλόγων που έχει ρίζα στον καθορισμένο κατάλογο. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Επιστρέφει τον ριζικό κατάλογο της καθορισμένης διαδρομής. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Αναζητά τα αρχεία που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε όλο το δέντρο καταλόγων που έχει ρίζα στον καθορισμένο κατάλογο. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Αναζητά τα αρχεία και τους καταλόγους που ικανοποιούν τα καθορισμένα κριτήρια αναζήτησης είτε στον καθορισμένο κατάλογο είτε σε όλο το δέντρο καταλόγων που έχει ρίζα στον καθορισμένο κατάλογο. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Επιστρέφει την ώρα τελευταίας πρόσβασης της καθορισμένης οντότητας ως τοπική ώρα. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Επιστρέφει την ώρα τελευταίας πρόσβασης της καθορισμένης οντότητας ως ώρα UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Επιστρέφει την ώρα τελευταίας εγγραφής της καθορισμένης οντότητας ως τοπική ώρα. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Επιστρέφει την ώρα τελευταίας εγγραφής της καθορισμένης οντότητας ως ώρα UTC. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Επιστρέφει ένα shared pointer στο αντικείμενο [DirectoryInfo](../directoryinfo/) που αντιπροσωπεύει τον γονικό κατάλογο της καθορισμένης οντότητας. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Μετακινεί την καθορισμένη οντότητα στη νέα θέση. Εάν η οντότητα προς μετακίνηση είναι κατάλογος, μετακινείται μαζί με όλο το περιεχόμενό του. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ορίζει την ώρα δημιουργίας της καθορισμένης οντότητας ως τοπική ώρα. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ορίζει την ώρα δημιουργίας της καθορισμένης οντότητας ως ώρα UTC. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Ορίζει τον τρέχοντα κατάλογο. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ορίζει την ώρα τελευταίας πρόσβασης της καθορισμένης οντότητας ως τοπική ώρα. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ορίζει την ώρα τελευταίας πρόσβασης της καθορισμένης οντότητας ως ώρα UTC. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ορίζει την ώρα τελευταίας εγγραφής της καθορισμένης οντότητας ως τοπική ώρα. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ορίζει την ώρα τελευταίας εγγραφής της καθορισμένης οντότητας ως ώρα UTC. |

## Τύποι

| Τύπος | Περιγραφή |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Μια εναλλακτική ονομασία για έναν shared pointer σε αντικείμενο IEnumerable που διαθέτει στοιχεία σε ένα σύνολο αντικειμένων [String](../../system/string/). |

## Παρατηρήσεις



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Δημιουργήστε συμβολοσειρές που περιέχουν διαδρομές σε καταλόγους.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Ελέγξτε αν οι κατάλογοι υπάρχουν.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Εμφανίστε τις πληροφορίες του προσωρινού καταλόγου.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την παρακάτω έξοδο:
Ο κατάλογος 'C:\' υπάρχει.
Ο κατάλογος 'C:\Some directory' δεν υπάρχει.
Ο κατάλογος 'C:\Users\lanor\AppData\Local\Temp\' υπάρχει.
Ώρα δημιουργίας: 27.08.2021 14:21:42
Ώρα τελευταίας πρόσβασης: 07.10.2021 12:16:41
Ώρα τελευταίας εγγραφής: 07.10.2021 12:16:41
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)
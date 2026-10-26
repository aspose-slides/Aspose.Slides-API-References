---
title: "System::Collections"
second_title: Αναφορά API Aspose.Slides για C++
description: 
type: docs
weight: 300
url: /el/system.collections/
---
## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) από bits που μπορούν να προσεγγιστούν με δείκτη. Τα αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο με τη συνάρτηση [System::MakeObject()](../system/makeobject/). Ποτέ μην δημιουργείτε παράδειγμα αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα να τυλίγετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../system/smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να τη μεταβιβάζετε σε συναρτήσεις ως όρισμα. |
| [BitArrayPtr](./bitarrayptr/) | Δείκτης προς [BitArray](./bitarray/). Αυτός ο τύπος είναι δείκτης για τη διαχείριση της διαγραφής άλλων αντικειμένων. Θα πρέπει να καταλαμβάνεται στη στοίβα και να μεταβιβάζεται σε συναρτήσεις είτε με τιμή είτε με σταθερή αναφορά. |
| [CollectionBase](./collectionbase/) | Παρέχει μια αφηρημένη βασική κλάση για μια συλλογή με αυστηρά τυποποιημένα στοιχεία. |
| [ICollection](./icollection/) | Ορίζει διεπαφή μη γενικής συλλογής. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) είναι η βασική διεπαφή για όλες τις μη-γενικές συλλογές που μπορούν να απαριθμηθούν. |
| [IEnumerator](./ienumerator/) | Διεπαφή του αλγορίθμου επανάληψης (enumerator) που μπορεί να χρησιμοποιηθεί για την επανάληψη σε κάποιο στοιχεία. Τα αντικείμενα αυτής της κλάσης πρέπει να καταλαμβάνονται μόνο με τη συνάρτηση [System::MakeObject()](../system/makeobject/). Ποτέ μην δημιουργείτε παράδειγμα αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα να τυλίγετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../system/smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να τη μεταβιβάζετε σε συναρτήσεις ως όρισμα. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Περιτύλιγμα που δημιουργεί μη-γενική υλοποίηση [IEnumerator](./ienumerator/) πάνω από τον γενικό Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) - περιτύλιγμα για τους τύπους αναφοράς. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Περιτύλιγμα που δημιουργεί μη-γενική υλοποίηση [IEnumerator](./ienumerator/) πάνω από τον γενικό Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) - περιτύλιγμα για τους τύπους τιμών. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) Αντιπροσωπεύει μια μη-γενική συλλογή αντικειμένων που μπορούν να προσπελαστούν ατομικά με δείκτη. |
| [IListImplRefType](./ilistimplreftype/) | Stub που υλοποιεί τη διεπαφή [System::Collections::IList](./ilist/) σε αντικείμενο [System::Collections::Generic::List](../system.collections.generic/list/) Υλοποίηση για τύπους αναφοράς. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub που υλοποιεί τη διεπαφή [System::Collections::IList](./ilist/) σε αντικείμενο [System::Collections::Generic::List](../system.collections.generic/list/) Υλοποίηση για τύπους τιμών. |
| [IListWrapper](./ilistwrapper/) | Διεπαφή για την υποστήριξη μετατροπής (casting) από γενική σε μη-γενική συλλογή. |
| [Invalidatable](./invalidatable/) | Κλάση που καθιστά δυνατό τον εντοπισμό της κατάστασης των απογόνων της μέσω αντικειμένων [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | Κλάση που υλοποιεί ιχνηλάτες αντικειμένων [Invalidatable](./invalidatable/). |
---
title: MakeRelative()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει τη διαφορά μεταξύ δύο εμφανίσεων του Uri.
type: docs
weight: 365
url: /el/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) μέθοδος

Καθορίζει τη διαφορά μεταξύ δύο εμφανίσεων του [Uri](../).

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### Παραμέτρους

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Το URI για σύγκριση με το τρέχον URI |

### Τιμή επιστροφής

Εάν το όνομα κεντρικού υπολογιστή και το σχήμα των URI που αντιπροσωπεύονται από το τρέχον αντικείμενο και **toUri** είναι τα ίδια, τότε αυτή η μέθοδος επιστρέφει ένα [String](../../string/) που αντιπροσωπεύει ένα σχετικό [Uri](../), το οποίο όταν προσαρτηθεί στην τρέχουσα εμφάνιση του URI, δίνει **toUri**. Εάν το όνομα κεντρικού υπολογιστή ή το σχήμα διαφέρουν, τότε αυτή η μέθοδος επιστρέφει ένα [String](../../string/) που αντιπροσωπεύει την παράμετρο **uri**.

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [Uri](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
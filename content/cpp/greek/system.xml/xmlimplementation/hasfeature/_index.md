---
title: HasFeature()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δοκιμάζει εάν η υλοποίηση του Μοντέλου Αντικειμένου Εγγράφου (DOM) υλοποιεί μια συγκεκριμένη δυνατότητα.
type: docs
weight: 14
url: /el/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) μέθοδος

Δοκιμάζει αν η υλοποίηση του Μοντέλου Εγγράφου [Object](../../../system/object/) (DOM) υλοποιεί μια συγκεκριμένη δυνατότητα.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | Το όνομα του πακέτου της δυνατότητας που θα δοκιμαστεί. Αυτό το όνομα δεν διακρίνει πεζά-κεφαλαία. |
| strVersion | const [String](../../../system/string/)\& | Αυός είναι ο αριθμός έκδοσης του ονόματος του πακέτου που θα δοκιμαστεί. Εάν η έκδοση δεν έχει καθοριστεί (**nullptr**), η υποστήριξη οποιασδήποτε έκδοσης της δυνατότητας κάνει τη μέθοδο να επιστρέφει **true**. |

### Τιμή Επιστροφής

**true** εάν η δυνατότητα υλοποιείται στην καθορισμένη έκδοση· διαφορετικά, **false**.

## Σχόλια

Ο παρακάτω πίνακας εμφανίζει τους συνδυασμούς που κάνουν το **HasFeature** να επιστρέφει **true**.

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XmlImplementation](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
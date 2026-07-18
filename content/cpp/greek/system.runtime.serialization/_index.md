---
title: "System::Runtime::Serialization"
second_title: "Αναφορά API του Aspose.Slides για C++"
description: 
type: docs
weight: 794
url: /el/system.runtime.serialization/
---
## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Αντιπροσωπεύει μια βασική υλοποίηση του [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) διεπαφή. |
| [IFormatterConverter](./iformatterconverter/) | Παρέχει τη σύνδεση μεταξύ ενός στιγμιότυπου του [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) και της κλάσης που παρέχεται από τον διαμορφωτή, η οποία είναι πιο κατάλληλη για την ανάλυση των δεδομένων μέσα στο [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Διεπαφή αντικειμένου που μπορεί να σειριοποιηθεί. Αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../system/makeobject/). Ποτέ μην δημιουργήσετε στιγμιότυπο αυτού του τύπου στο stack ή χρησιμοποιώντας operator new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα επαλήθευσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα. |
| [SerializationInfo](./serializationinfo/) | Διατηρεί σύνολο ονομαστικών πεδίων που αντιπροσωπεύουν σειριοποιημένο αντικείμενο. Δεν έχει υλοποιηθεί. Αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../system/makeobject/). Ποτέ μην δημιουργήσετε στιγμιότυπο αυτού του τύπου στο stack ή χρησιμοποιώντας operator new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα επαλήθευσης. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να την περάσετε σε συναρτήσεις ως όρισμα. |
| [StreamingContext](./streamingcontext/) | Dummy κλάση για να κάνει τις κλάσεις που μεταφράζονται με χρήση StreamingContext να μεταγλωττίζονται. Μην διαχειρίζεστε στιγμιότυπα αυτής της κλάσης με [SmartPtr](../system/smartptr/), πρέπει να εκχωρούνται μόνο στο stack. |
## Ορισμοί τύπων

| Ορισμός τύπου | Περιγραφή |
| --- | --- |
| [SerializationException](./serializationexception/) |  |
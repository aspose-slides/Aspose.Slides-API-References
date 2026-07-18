---
title: ValidationType
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει τον τύπο επαλήθευσης που θα εκτελεστεί.
type: docs
weight: 729
url: /el/system.xml/validationtype/
---
## ValidationType enum

Καθορίζει τον τύπο επαλήθευσης που θα εκτελεστεί.

```cpp
enum class ValidationType
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | 0 | Δεν εκτελείται καμία επαλήθευση και δεν προβάλλονται σφάλματα επαλήθευσης. Αυτή η ρύθμιση δημιουργεί έναν συμβατό με XML 1.0 μη-επαληθευτικό parser. |
| Auto | 1 | Επαληθεύει εφόσον βρεθεί πληροφορία DTD ή σχήματος. |
| DTD | 2 | Επαληθεύει σύμφωνα με το DTD. |
| XDR | 3 | Επαληθεύει σύμφωνα με σχήματα XML-Data Reduced (XDR), συμπεριλαμβανομένων ενσωματωμένων σχήματων XDR. Τα σχήματα XDR αναγνωρίζονται με το πρόθεμα ονοματοχώρου **x-schema** ή τη τιμή [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Επαληθεύει σύμφωνα με σχήματα XML [Schema](../../system.xml.schema/) (γλώσσα ορισμού XSD), συμπεριλαμβανομένων ενσωματωμένων XML Σχημάτων. Τα XML Σχήματα συνδέονται με URI ονοματοχώρων είτε χρησιμοποιώντας το χαρακτηριστικό **schemaLocation** είτε τα παρεχόμενα **Schemas**. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Xml](../)
* Βιβλιοθήκη [Aspose.Slides](../../)
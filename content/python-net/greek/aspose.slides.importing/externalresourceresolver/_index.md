---
title: ExternalResourceResolver class
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver κλάση

Κλάση Callback που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Html, Svg.  
Η χρήση αυτού του επιλυτή θα μπορούσε να δημιουργήσει μια ευπάθεια όταν ένα αρχείο HTML ή SVG που παρέχεται από τον πελάτη επιτρέπει στο λογισμικό του διακομιστή να αποκτήσει τοπικό ή δικτυακό αρχείο. Χρησιμοποιήστε το με προσοχή. Συνιστάται να μην ορίζεται το ExternalResourceResolver καθόλου (μόνο τα ενσωματωμένα αντικείμενα θα διαβαστούν) ή να δημιουργηθεί κάποια υποκλάση που ελέγχει εάν το καθορισμένο uri είναι έγκυρο.

Ο τύπος ExternalResourceResolver εκθέτει τα παρακάτω μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/el/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Επιλύει το απόλυτο URI από το βασικό και τα σχετικά URIs. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/el/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο. |

### Δείτε επίσης
* μονάδα [`aspose.slides.importing`](/slides/python-net/el/aspose.slides.importing)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
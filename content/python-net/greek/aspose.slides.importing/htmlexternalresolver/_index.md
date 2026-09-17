---
title: HtmlExternalResolver class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver κλάση

Αντικείμενο κλήσης επιστροφής που χρησιμοποιείται από τη διαδικασία εισαγωγής HTML για την απόκτηση αντικειμένων που αναφέρονται, όπως εικόνες.  
Η χρήση αυτού του resolver μπορεί να δημιουργήσει μια ευπάθεια όταν το αρχείο HTML που παρέχεται από τον πελάτη κάνει το λογισμικό του διακομιστή να αποκτήσει τοπικό ή δικτυακό αρχείο. Χρησιμοποιήστε το με προσοχή. Συνιστάται να μην καθορίζετε καθόλου το HtmlExternalResolver (θα διαβαστούν μόνο τα ενσωματωμένα αντικείμενα) ή να δημιουργήσετε κάποιο υποκλάδο που ελέγχει αν το συγκεκριμένο uri είναι έγκυρο.

Ο τύπος HtmlExternalResolver εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/el/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Επιλύει το απόλυτο URI από τα βασικά και σχετικά URIs. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/el/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο. |

### Δείτε επίσης
* μονάδα [`aspose.slides.importing`](/slides/python-net/el/aspose.slides.importing)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
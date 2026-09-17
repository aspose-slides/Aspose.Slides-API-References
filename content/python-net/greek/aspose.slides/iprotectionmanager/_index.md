---
title: IProtectionManager class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/iprotectionmanager/
---
## IProtectionManager κλάση

Διαχείριση προστασίας κωδικού πρόσβασης παρουσίασης.

Ο τύπος IProtectionManager εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/el/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Αυτή η ιδιότητα έχει νόημα, εάν η παρουσίαση είναι προστατευμένη με κωδικό.<br/>            Αν είναι true τότε οι ιδιότητες του εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης.<br/>            Αν είναι false τότε οι ιδιότητες του εγγράφου είναι δημόσιες ενώ η παρουσίαση είναι κρυπτογραφημένη.<br/>            Read/write **bool**. |
| [`is_encrypted`](/slides/python-net/el/aspose.slides/iprotectionmanager/is_encrypted/) | Λαμβάνει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι κρυπτογραφημένη.<br/>            Read-only **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/el/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Αυτή η ιδιότητα έχει νόημα, εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό και οι ιδιότητες του εγγράφου <br/>            αυτού του αρχείου είναι δημόσιες.<br/>            Η τιμή true σημαίνει ότι μόνο οι ιδιότητες του εγγράφου φορτώνονται από ένα κρυπτογραφημένο <br/>            αρχείο παρουσίασης χωρίς χρήση κωδικού.<br/>            Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση φορτώνεται με τη χρήση του σωστού <br/>            κωδικού, όχι μόνο οι ιδιότητες του εγγράφου φορτώνονται.<br/>            Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας είναι πάντα false.<br/>            Εάν οι ιδιότητες του εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες, η τιμή της ιδιότητας είναι πάντα false.<br/>            Εάν PresentationEx.EncryptDocumentProperties είναι true, τότε η τιμή της ιδιότητας IsOnlyDocumentPropertiesLoaded <br/>            είναι πάντα false.<br/>            Read-only **bool**. |
| [`is_write_protected`](/slides/python-net/el/aspose.slides/iprotectionmanager/is_write_protected/) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσίαση είναι προστατευμένη από εγγραφή.<br/>            Read-only **bool**. |
| [`encryption_password`](/slides/python-net/el/aspose.slides/iprotectionmanager/encryption_password/) | Επιστρέφει τον κωδικό κρυπτογράφησης.<br/>            Read-only **str**. |
| [`read_only_recommended`](/slides/python-net/el/aspose.slides/iprotectionmanager/read_only_recommended/) | Λαμβάνει ή ορίζει πρόταση μόνο-ανάγνωσης.<br/>            Read/write **bool**. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/el/aspose.slides/iprotectionmanager/encrypt/#str) | Κρυπτογραφεί την παρουσίαση με τον καθορισμένο κωδικό. |
| [`remove_encryption(self)`](/slides/python-net/el/aspose.slides/iprotectionmanager/remove_encryption/#) | Αφαιρεί την κρυπτογράφηση. |
| [`set_write_protection(self, password)`](/slides/python-net/el/aspose.slides/iprotectionmanager/set_write_protection/#str) | Ορίζει προστασία εγγραφής για αυτήν την παρουσίαση με τον καθορισμένο κωδικό. |
| [`remove_write_protection(self)`](/slides/python-net/el/aspose.slides/iprotectionmanager/remove_write_protection/#) | Αφαιρεί την προστασία εγγραφής για αυτήν την παρουσίαση. |
| [`check_write_protection(self, password)`](/slides/python-net/el/aspose.slides/iprotectionmanager/check_write_protection/#str) | Καθορίζει αν μια παρουσίαση είναι προστατευμένη με κωδικό για τροποποίηση. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
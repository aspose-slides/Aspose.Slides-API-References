---
title: ProtectionManager class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/protectionmanager/
---
## ProtectionManager κλάση

Διαχείριση προστασίας Presentation με κωδικό πρόσβασης.

Ο τύπος ProtectionManager εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/el/aspose.slides/protectionmanager/encrypt_document_properties/) | Αυτή η ιδιότητα έχει νόημα, εάν η παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης.<br/>            Εάν είναι αληθής, τότε οι ιδιότητες εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης.<br/>            Εάν είναι ψευδής, τότε οι ιδιότητες εγγράφου είναι δημόσιες ενώ η παρουσίαση είναι κρυπτογραφημένη.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`is_encrypted`](/slides/python-net/el/aspose.slides/protectionmanager/is_encrypted/) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι κρυπτογραφημένη.<br/>            Μόνο για ανάγνωση **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/el/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Αυτή η ιδιότητα έχει νόημα, εάν το αρχείο παρουσίασης προστατεύεται με κωδικό πρόσβασης και οι ιδιότητες εγγράφου αυτού του αρχείου είναι δημόσιες.<br/>            Η τιμή αληθής σημαίνει ότι μόνο οι ιδιότητες εγγράφου φορτώνονται από ένα κρυπτογραφημένο<br/>            αρχείο παρουσίασης χωρίς χρήση κωδικού.<br/>            Η τιμή ψευδής σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση φορτώνεται με τη χρήση του σωστού<br/>            κωδικού, όχι μόνο οι ιδιότητες εγγράφου.<br/>            Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, τότε η τιμή της ιδιότητας είναι πάντα ψευδής.<br/>            Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες, τότε η τιμή της ιδιότητας είναι πάντα ψευδής.<br/>            Εάν Presentation.EncryptDocumentProperties είναι αληθής, τότε η τιμή της ιδιότητας IsOnlyDocumentPropertiesLoaded είναι πάντα ψευδής.<br/>            Μόνο για ανάγνωση **bool**. |
| [`is_write_protected`](/slides/python-net/el/aspose.slides/protectionmanager/is_write_protected/) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσίαση είναι προστατευμένη από εγγραφή.<br/>            Μόνο για ανάγνωση **bool**. |
| [`encryption_password`](/slides/python-net/el/aspose.slides/protectionmanager/encryption_password/) | Επιστρέφει τον κωδικό πρόσβασης που χρησιμοποιείται για την κρυπτογράφηση της παρουσίασης.<br/>            Μόνο για ανάγνωση **str**. |
| [`read_only_recommended`](/slides/python-net/el/aspose.slides/protectionmanager/read_only_recommended/) | Επιστρέφει ή ορίζει την πρόταση μόνο για ανάγνωση.<br/>            Ανάγνωση/εγγραφή **bool**. |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/el/aspose.slides/protectionmanager/encrypt/#str) | Κρυπτογραφεί την Presentation με τον καθορισμένο κωδικό πρόσβασης. |
| [`remove_encryption(self)`](/slides/python-net/el/aspose.slides/protectionmanager/remove_encryption/#) | Αφαιρεί την κρυπτογράφηση. |
| [`set_write_protection(self, password)`](/slides/python-net/el/aspose.slides/protectionmanager/set_write_protection/#str) | Ορίζει προστασία εγγραφής για αυτήν την παρουσίαση με τον καθορισμένο κωδικό πρόσβασης. |
| [`remove_write_protection(self)`](/slides/python-net/el/aspose.slides/protectionmanager/remove_write_protection/#) | Αφαιρεί την προστασία εγγραφής για αυτήν την παρουσίαση. |
| [`check_write_protection(self, password)`](/slides/python-net/el/aspose.slides/protectionmanager/check_write_protection/#str) | Καθορίζει εάν μια παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης για τροποποίηση. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
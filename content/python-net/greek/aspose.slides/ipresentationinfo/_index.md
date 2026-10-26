---
title: IPresentationInfo class
second_title: Aspose.Slides για Python μέσω .NET API αναφορά
description: 
type: docs
url: /el/aspose.slides/ipresentationinfo/
---
## IPresentationInfo κλάση

Πληροφορίες σχετικά με το αρχείο παρουσίασης

Ο τύπος IPresentationInfo εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_encrypted`](/slides/python-net/el/aspose.slides/ipresentationinfo/is_encrypted/) | Επιστρέφει True εάν η συνδεδεμένη παρουσίαση είναι κρυπτογραφημένη, διαφορετικά False.<br/>            Μόνο για ανάγνωση **bool**. |
| [`is_password_protected`](/slides/python-net/el/aspose.slides/ipresentationinfo/is_password_protected/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η συνδεδεμένη παρουσίαση προστατεύεται με κωδικό για άνοιγμα. |
| [`is_write_protected`](/slides/python-net/el/aspose.slides/ipresentationinfo/is_write_protected/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η συνδεδεμένη παρουσίαση είναι προστατευμένη από εγγραφή. |
| [`load_format`](/slides/python-net/el/aspose.slides/ipresentationinfo/load_format/) | Επιστρέφει τη μορφή της συνδεδεμένης παρουσίασης.<br/>            Μόνο για ανάγνωση [`LoadFormat`](/slides/python-net/el/aspose.slides/loadformat). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/el/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Γράφει τη συνδεδεμένη παρουσίαση σε ροή. |
| [`write_binded_presentation(self, file)`](/slides/python-net/el/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Γράφει τη συνδεδεμένη παρουσίαση σε αρχείο. |
| [`check_password(self, password)`](/slides/python-net/el/aspose.slides/ipresentationinfo/check_password/#str) | Ελέγχει εάν ένας κωδικός είναι σωστός για παρουσίαση προστατευμένη με κωδικό ανοίγματος. |
| [`check_write_protection(self, password)`](/slides/python-net/el/aspose.slides/ipresentationinfo/check_write_protection/#str) | Ελέγχει εάν ο κωδικός για τροποποίηση είναι σωστός για μια παρουσίαση προστατευμένη από εγγραφή. |
| [`read_document_properties(self)`](/slides/python-net/el/aspose.slides/ipresentationinfo/read_document_properties/#) | Επιστρέφει τις ιδιότητες του εγγράφου της συνδεδεμένης παρουσίασης. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/el/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Ενημερώνει τις ιδιότητες της συνδεδεμένης παρουσίασης. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
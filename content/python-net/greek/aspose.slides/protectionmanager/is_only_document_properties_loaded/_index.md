---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded ιδιότητα

Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό και οι ιδιότητες εγγράφου
            αυτού του αρχείου είναι δημόσιες.
Η τιμή true σημαίνει ότι μόνο οι ιδιότητες εγγράφου φορτώνονται από ένα κρυπτογραφημένο
            αρχείο παρουσίασης χωρίς χρήση κωδικού.
Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση φορτώνεται με τη χρήση του σωστού
            κωδικού, όχι μόνο οι ιδιότητες εγγράφου φορτώνονται.
Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, τότε η τιμή της ιδιότητας είναι πάντα false.
Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες, τότε η τιμή της ιδιότητας είναι πάντα false.
Εάν Presentation.EncryptDocumentProperties είναι true, τότε η τιμή της ιδιότητας IsOnlyDocumentPropertiesLoaded
            η τιμή της ιδιότητας είναι πάντα false.
Μόνο-ανάγνωση **bool**.

### Ορισμός:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Δείτε επίσης
* κλάση [`ProtectionManager`](/slides/python-net/el/aspose.slides/protectionmanager)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
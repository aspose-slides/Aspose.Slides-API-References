---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded ιδιότητα
Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό πρόσβασης και οι ιδιότητες εγγράφου αυτού του αρχείου είναι δημόσιες.
Η τιμή true σημαίνει ότι μόνο οι ιδιότητες εγγράφου φορτώνονται από ένα κρυπτογραφημένο αρχείο παρουσίασης χωρίς χρήση κωδικού πρόσβασης.
Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση φορτώνεται με τη χρήση του σωστού κωδικού πρόσβασης, όχι μόνο οι ιδιότητες εγγράφου.
Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, τότε η τιμή της ιδιότητας είναι πάντα false.
Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες, τότε η τιμή της ιδιότητας είναι πάντα false.
Εάν το PresentationEx.EncryptDocumentProperties είναι true, τότε η τιμή της ιδιότητας IsOnlyDocumentPropertiesLoaded είναι πάντα false.
Μόνο για ανάγνωση **bool**.

### Ορισμός:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Δείτε επίσης
* class [`IProtectionManager`](/slides/python-net/el/aspose.slides/iprotectionmanager)
* module [`aspose.slides`](/slides/python-net/el/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
---
title: only_load_document_properties property
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties ιδιότητα
Αυτή η ιδιότητα έχει νόημα, εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό.
            Η τιμή true σημαίνει ότι πρέπει να φορτωθούν μόνο οι ιδιότητες του εγγράφου από ένα κρυπτογραφημένο 
            αρχείο παρουσίασης και ο κωδικός πρέπει να αγνοηθεί.
            Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση πρέπει να φορτωθεί με τη χρήση του σωστού 
            κωδικού.
            Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, τότε η τιμή της ιδιότητας αγνοείται πάντα.
            Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή της ιδιότητας είναι true τότε
            οι ιδιότητες εγγράφου δεν μπορούν να φορτωθούν και θα γίνει εξαίρεση.
            Αναγνώσιμη-εγγράψιμη **bool**.

### Ορισμός:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### Δείτε επίσης
* κλάση [`ILoadOptions`](/slides/python-net/el/aspose.slides/iloadoptions)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
---
title: Presentation constructor
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από την αρχή.
            Η δημιουργημένη παρουσίαση έχει μία κενή διαφάνεια.


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
Αυτός ο κατασκευαστής δημιουργεί νέα παρουσίαση από την αρχή.
            Η δημιουργημένη παρουσίαση έχει μία κενή διαφάνεια.


```python
def __init__(self, load_options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/el/aspose.slides/loadoptions) | Επιπρόσθετες επιλογές φόρτωσης. |


## __init__(self, stream) {#iorawiobase}
Ο κύριος μηχανισμός για την ανάγνωση μιας υπάρχουσας Παρουσίασης.


```python
def __init__(self, stream):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή εισόδου. |


## __init__(self, file) {#str}
Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή αρχείου προέλευσης από την οποία
             διαβάζονται τα περιεχόμενα της Παρουσίασης.


```python
def __init__(self, file):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file | **str** | Αρχείο εισόδου. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εγείρεται όταν το αρχείο εισόδου έχει μηδενικό μήκος |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Ο κύριος μηχανισμός για την ανάγνωση μιας υπάρχουσας Παρουσίασης.


```python
def __init__(self, stream, load_options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή εισόδου. |
| load_options | [`LoadOptions`](/slides/python-net/el/aspose.slides/loadoptions) | Επιπρόσθετες επιλογές φόρτωσης. |


## __init__(self, file, load_options) {#str-loadoptions}
Αυτός ο κατασκευαστής λαμβάνει τη διαδρομή αρχείου προέλευσης από την οποία
            διαβάζονται τα περιεχόμενα της Παρουσίασης.


```python
def __init__(self, file, load_options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file | **str** | Αρχείο εισόδου. |
| load_options | [`LoadOptions`](/slides/python-net/el/aspose.slides/loadoptions) | Επιπρόσθετες επιλογές φόρτωσης. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εγείρεται όταν το αρχείο εισόδου έχει μηδενικό μήκος |



### Δείτε επίσης
* κλάση [`LoadOptions`](/slides/python-net/el/aspose.slides/loadoptions)
* κλάση [`Presentation`](/slides/python-net/el/aspose.slides/presentation)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
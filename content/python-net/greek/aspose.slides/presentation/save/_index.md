---
title: save method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/presentation/save/
weight: 100
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα σύνολο αρχείων που αντιπροσωπεύουν σήμανση XAML.


```python
def save(self, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/el/aspose.slides.export.xaml/ixamloptions) | Οι επιλογές μορφής XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα αρχείο με το καθορισμένο μορφότυπο.


```python
def save(self, fname, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** | Διαδρομή προς το δημιουργημένο αρχείο. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαγόμενων δεδομένων. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με το καθορισμένο μορφότυπο.


```python
def save(self, stream, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή εξόδου. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαγόμενων δεδομένων. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με το καθορισμένο μορφότυπο και με πρόσθετες επιλογές.


```python
def save(self, stream, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή εξόδου. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαγόμενων δεδομένων. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Επιπλέον επιλογές μορφής. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε <br/>            μορφή εκτός Office 2007-2010 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ένα αρχείο με το καθορισμένο μορφότυπο διατηρώντας τον αριθμό της σελίδας.


```python
def save(self, fname, slides, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** | Διαδρομή προς το δημιουργημένο αρχείο. |
| slides | **List[int]** | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαγόμενων δεδομένων. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Όταν η παράμετρος stream ή slides είναι None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδας. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Όταν χρησιμοποιείται μη υποστηριζόμενη SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με το καθορισμένο μορφότυπο διατηρώντας τον αριθμό της σελίδας.


```python
def save(self, stream, slides, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή εξόδου. |
| slides | **List[int]** | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαγόμενων δεδομένων. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ένα αρχείο με το καθορισμένο μορφότυπο διατηρώντας τον αριθμό της σελίδας.


```python
def save(self, fname, slides, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** | Διαδρομή προς το δημιουργημένο αρχείο. |
| slides | **List[int]** | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαγόμενων δεδομένων. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Επιπλέον επιλογές μορφής. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με το καθορισμένο μορφότυπο διατηρώντας τον αριθμό της σελίδας.


```python
def save(self, stream, slides, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή εξόδου. |
| slides | **List[int]** | Πίνακας με θέσεις διαφανειών, ξεκινώντας από το 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαγόμενων δεδομένων. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Επιπλέον επιλογές μορφής. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Όταν η παράμετρος stream ή slides είναι None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδας. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Όταν χρησιμοποιείται μη υποστηριζόμενη SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Δείτε επίσης
* κλάση [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions)
* κλάση [`IXamlOptions`](/slides/python-net/el/aspose.slides.export.xaml/ixamloptions)
* κλάση [`Presentation`](/slides/python-net/el/aspose.slides/presentation)
* απαρίθμηση [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
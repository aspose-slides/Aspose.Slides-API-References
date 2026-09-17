---
title: save method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα σύνολο αρχείων που αντιπροσωπεύουν σήμανση XAML markup.


```python
def save(self, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/el/aspose.slides.export.xaml/ixamloptions) | Οι επιλογές μορφής XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή.


```python
def save(self, fname, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** | Διαδρομή του δημιουργημένου αρχείου. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαχθέντων δεδομένων. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή.


```python
def save(self, stream, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή εξόδου. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαχθέντων δεδομένων. |


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
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή και με επιπρόσθετες επιλογές.


```python
def save(self, stream, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή εξόδου. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαχθέντων δεδομένων. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Επιπρόσθετες επιλογές μορφής. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | If you try to save encrypted file in <br/>            none Office 2007-2010 format |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή διατηρώντας τον αριθμό σελίδας.


```python
def save(self, fname, slides, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** | Διαδρομή του δημιουργημένου αρχείου. |
| slides | **List[int]** | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαχθέντων δεδομένων. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Όταν η παράμετρος stream ή slides είναι None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδας. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Όταν χρησιμοποιείται μη υποστηριζόμενη SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή διατηρώντας τον αριθμό σελίδας.


```python
def save(self, stream, slides, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή εξόδου. |
| slides | **List[int]** | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαχθέντων δεδομένων. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με την καθορισμένη μορφή διατηρώντας τον αριθμό σελίδας.


```python
def save(self, fname, slides, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** | Διαδρομή του δημιουργημένου αρχείου. |
| slides | **List[int]** | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαχθέντων δεδομένων. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Επιπρόσθετες επιλογές μορφής. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή με την καθορισμένη μορφή διατηρώντας τον αριθμό σελίδας.


```python
def save(self, stream, slides, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ροή εξόδου. |
| slides | **List[int]** | Πίνακας με τις θέσεις των διαφανειών, ξεκινώντας από 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Μορφή των εξαχθέντων δεδομένων. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Επιπρόσθετες επιλογές μορφής. |

### Εξαιρέσεις

| Exception | Description |
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
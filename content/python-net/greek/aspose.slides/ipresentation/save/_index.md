---
title: save method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ένα σύνολο αρχείων που αντιπροσωπεύουν σήμανση XAML markup.


```python
def save(self, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/el/aspose.slides.export.xaml/ixamloptions) | The XAML format options. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή.


```python
def save(self, fname, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή στην καθορισμένη μορφή.


```python
def save(self, stream, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Format of the exported data. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή και με πρόσθετες επιλογές.


```python
def save(self, fname, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Additional format options. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Αποθηκεύει όλες τις διαφάνειες μιας παρουσίασης σε ροή στην καθορισμένη μορφή και με πρόσθετες επιλογές.


```python
def save(self, stream, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Additional format options. |

### Εξαιρέσεις

| Exception | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Εάν προσπαθήσετε να αποθηκεύσετε κρυπτογραφημένο αρχείο σε <br/>            μη-Office 2007-2010 μορφή |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή.


```python
def save(self, fname, slides, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Format of the exported data. |

### Εξαιρέσεις

| Exception | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Όταν η παράμετρος stream ή slides είναι None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδων. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Όταν χρησιμοποιείται μια μη υποστηριζόμενη SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή στην καθορισμένη μορφή.


```python
def save(self, stream, slides, format):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Format of the exported data. |

### Εξαιρέσεις

| Exception | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Όταν η παράμετρος stream ή slides είναι None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδων. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Όταν χρησιμοποιείται μια μη υποστηριζόμενη SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε αρχείο με τη συγκεκριμένη μορφή.


```python
def save(self, fname, slides, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Additional format options. |

### Εξαιρέσεις

| Exception | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Όταν η παράμετρος stream ή slides είναι None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδων. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Όταν χρησιμοποιείται μια μη υποστηριζόμενη SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Αποθηκεύει τις καθορισμένες διαφάνειες μιας παρουσίασης σε ροή στην καθορισμένη μορφή.


```python
def save(self, stream, slides, format, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Additional format options. |

### Εξαιρέσεις

| Exception | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Όταν η παράμετρος stream ή slides είναι None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Όταν η παράμετρος slides περιέχει λανθασμένους αριθμούς σελίδων. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Όταν χρησιμοποιείται μια μη υποστηριζόμενη SaveFormat, π.χ. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Δείτε επίσης
* κλάση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation)
* κλάση [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions)
* κλάση [`IXamlOptions`](/slides/python-net/el/aspose.slides.export.xaml/ixamloptions)
* απαρίθμηση [`SaveFormat`](/slides/python-net/el/aspose.slides.export/saveformat)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
---
title: process method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Συγχωνεύει πολλαπλές παρουσιάσεις PowerPoint με την ίδια μορφή σε ένα ενιαίο αρχείο παρουσίασης.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| input_file_names | **List[str]** | Ένας πίνακας των ονομάτων των αρχείων εισόδου παρουσίασης. |
| output_file_name | **str** | Το όνομα του αρχείου εξόδου του τελικού συγχωνευμένου αρχείου παρουσίασης. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκκινείται όταν τα ονόματα αρχείων εισόδου δεν είναι έγκυρα ή οι μορφές δεν ταιριάζουν. |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
Συγχωνεύει πολλαπλές παρουσιάσεις PowerPoint με την ίδια μορφή σε ένα ενιαίο αρχείο παρουσίασης.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| input_file_names | **List[str]** | Ένας πίνακας των ονομάτων των αρχείων εισόδου παρουσίασης. |
| output_stream | **io.RawIOBase** | Το ρεύμα εξόδου. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκκινείται όταν τα ονόματα αρχείων εισόδου δεν είναι έγκυρα ή οι μορφές δεν ταιριάζουν. |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Συγχωνεύει πολλαπλές παρουσιάσεις PowerPoint με την ίδια μορφή σε ένα ενιαίο αρχείο παρουσίασης.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| input_file_names | **List[str]** | Ένας πίνακας των ονομάτων των αρχείων εισόδου παρουσίασης. |
| output_file_name | **str** | Το όνομα του αρχείου εξόδου του τελικού συγχωνευμένου αρχείου παρουσίασης. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Οι πρόσθετες επιλογές που καθορίζουν πώς αποθηκεύεται η συγχωνευμένη παρουσίαση. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκκινείται όταν τα ονόματα αρχείων εισόδου δεν είναι έγκυρα ή οι μορφές δεν ταιριάζουν. |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Συγχωνεύει πολλαπλές παρουσιάσεις PowerPoint με την ίδια μορφή σε ένα ενιαίο αρχείο παρουσίασης.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| input_file_names | **List[str]** | Ένας πίνακας των ονομάτων των αρχείων εισόδου παρουσίασης. |
| output_stream | **io.RawIOBase** | Το ρεύμα εξόδου. |
| options | [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions) | Οι πρόσθετες επιλογές που καθορίζουν πώς αποθηκεύεται η συγχωνευμένη παρουσίαση. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκκινείται όταν τα ονόματα αρχείων εισόδου δεν είναι έγκυρα ή οι μορφές δεν ταιριάζουν. |



### Δείτε επίσης
* κλάση [`ISaveOptions`](/slides/python-net/el/aspose.slides.export/isaveoptions)
* κλάση [`Merger`](/slides/python-net/el/aspose.slides.lowcode/merger)
* μονάδα [`aspose.slides.lowcode`](/slides/python-net/el/aspose.slides.lowcode)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
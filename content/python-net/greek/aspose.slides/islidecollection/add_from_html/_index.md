---
title: add_from_html method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

### Επιστρέφει

Προστέθηκαν διαφάνειες



```python
def add_from_html(self, html_text):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| html_text | **str** | Html προς προσθήκη. |


## add_from_html(self, html_stream) {#iorawiobase}
Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

### Επιστρέφει

Προστέθηκαν διαφάνειες



```python
def add_from_html(self, html_stream):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

### Επιστρέφει

Προστέθηκαν διαφάνειες.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| html_text | **str** | Html προς προσθήκη. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Αν αυτή η παράμετρος είναι None, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | **str** | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής.

### Επιστρέφει

Προστέθηκαν διαφάνειες.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Αν αυτή η παράμετρος είναι None, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | **str** | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |



### Δείτε επίσης
* κλάση [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver)
* κλάση [`ISlideCollection`](/slides/python-net/el/aspose.slides/islidecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
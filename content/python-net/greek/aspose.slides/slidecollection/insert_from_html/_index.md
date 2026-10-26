---
title: insert_from_html method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

### Επιστρέφει

Διαφάνειες που προστέθηκαν



```python
def insert_from_html(self, index, html_text):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Θέση εισαγωγής. |
| html_text | **str** | HTML προς προσθήκη. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

### Επιστρέφει

Διαφάνειες που προστέθηκαν



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Θέση εισαγωγής. |
| html_stream | **io.RawIOBase** | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

### Επιστρέφει

Διαφάνειες που προστέθηκαν



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Θέση εισαγωγής. |
| html_text | **str** | HTML προς προσθήκη. |
| use_slide_with_index_as_start | **bool** | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη.<br/><br/>            Εάν **true** , τότε η εισαγωγή δεδομένων θα ξεκινήσει από έναν κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη.<br/><br/>            Εάν **false** , τότε τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

### Επιστρέφει

Διαφάνειες που προστέθηκαν



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Θέση εισαγωγής. |
| html_stream | **io.RawIOBase** | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| use_slide_with_index_as_start | **bool** | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη.<br/><br/>            Εάν **true** , τότε η εισαγωγή δεδομένων θα ξεκινήσει από έναν κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη.<br/><br/>            Εάν **false** , τότε τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

### Επιστρέφει

Διαφάνειες που προστέθηκαν.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Θέση εισαγωγής. |
| html_text | **str** | HTML προς προσθήκη. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι None, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | **str** | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

### Επιστρέφει

Διαφάνειες που προστέθηκαν.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Θέση εισαγωγής. |
| html_stream | **io.RawIOBase** | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι None, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | **str** | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

### Επιστρέφει

Διαφάνειες που προστέθηκαν.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Θέση εισαγωγής. |
| html_text | **str** | HTML προς προσθήκη. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι None, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | **str** | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| use_slide_with_index_as_start | **bool** | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη.<br/><br/>            Εάν **true** , τότε η εισαγωγή δεδομένων θα ξεκινήσει από έναν κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη.<br/><br/>            Εάν **false** , τότε τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση.

### Επιστρέφει

Διαφάνειες που προστέθηκαν.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Θέση εισαγωγής. |
| html_stream | **io.RawIOBase** | Ένα αντικείμενο Stream που θα χρησιμοποιηθεί ως πηγή ενός αρχείου HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver) | Ένα αντικείμενο callback που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι None, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| uri | **str** | Ένα URI του καθορισμένου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |
| use_slide_with_index_as_start | **bool** | Αυτή η σημαία καθορίζει πώς θα ξεκινήσει η εισαγωγή: από μια νέα διαφάνεια ή από τη διαφάνεια με τον καθορισμένο δείκτη.<br/><br/>            Εάν **true** , τότε η εισαγωγή δεδομένων θα ξεκινήσει από έναν κενό χώρο στη διαφάνεια με τον καθορισμένο δείκτη.<br/><br/>            Εάν **false** , τότε τα δεδομένα θα προστεθούν στις δημιουργημένες διαφάνειες. |



### Δείτε επίσης
* κλάση [`IExternalResourceResolver`](/slides/python-net/el/aspose.slides.importing/iexternalresourceresolver)
* κλάση [`SlideCollection`](/slides/python-net/el/aspose.slides/slidecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
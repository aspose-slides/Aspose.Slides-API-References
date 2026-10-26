---
title: insert_auto_shape method
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση, εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου.

### Επιστρέφει

Το νέο δημιουργημένο [`IAutoShape`](/slides/python-net/el/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το νέο αυτόματο σχήμα. |
| shape_type | [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) | Το [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) του αυτόματου σχήματος προς εισαγωγή. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του σχήματος, σε σημεία. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση, προαιρετικά αρχικοποιώντας το με προεπιλεγμένο στυλ προτύπου.

### Επιστρέφει

Το νέο δημιουργημένο [`IAutoShape`](/slides/python-net/el/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το αυτόματο σχήμα. |
| shape_type | [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) | Το [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) του αυτόματου σχήματος προς εισαγωγή. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του σχήματος, σε σημεία. |
| create_from_template | **bool** | True για εφαρμογή προεπιλεγμένου στυλ προτύπου (συμπεριλαμβανομένου ενός μη κενό ονόματος, απλού στυλ και κεντρασμένου κειμένου); <br/><br/>false για δημιουργία του σχήματος με όλες τις ιδιότητες ορισμένες στις προεπιλογές. |



### Δείτε επίσης
* κλάση [`IAutoShape`](/slides/python-net/el/aspose.slides/iautoshape)
* κλάση [`ShapeCollection`](/slides/python-net/el/aspose.slides/shapecollection)
* απαρίθμηση [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
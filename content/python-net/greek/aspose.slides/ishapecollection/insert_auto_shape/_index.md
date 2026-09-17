---
title: insert_auto_shape method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου.

### Επιστρέφει

Το πρόσφατα δημιουργημένο [`IAutoShape`](/slides/python-net/el/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης που χρησιμοποιείται για την εισαγωγή του νέου αυτόματου σχήματος. |
| shape_type | [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) | Το [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) του αυτόματου σχήματος που θα εισαχθεί. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σχήματος, σε μονάδες σημείων. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σχήματος, σε μονάδες σημείων. |
| width | **float** | Το πλάτος του πλαισίου του σχήματος, σε μονάδες σημείων. |
| height | **float** | Το ύψος του πλαισίου του σχήματος, σε μονάδες σημείων. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά αρχικοποιώντας το με την προεπιλεγμένη διαμόρφωση προτύπου.

### Επιστρέφει

Το πρόσφατα δημιουργημένο [`IAutoShape`](/slides/python-net/el/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης που χρησιμοποιείται για την εισαγωγή του αυτόματου σχήματος. |
| shape_type | [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) | Το [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) του αυτόματου σχήματος που θα εισαχθεί. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σχήματος, σε μονάδες σημείων. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σχήματος, σε μονάδες σημείων. |
| width | **float** | Το πλάτος του πλαισίου του σχήματος, σε μονάδες σημείων. |
| height | **float** | Το ύψος του πλαισίου του σχήματος, σε μονάδες σημείων. |
| create_from_template | **bool** | True για εφαρμογή της προεπιλεγμένης διαμόρφωσης προτύπου (συμπεριλαμβανομένου ενός μη κενό ονόματος, απλού στυλ και κεντραρισμένου κειμένου); <br/><br/>            false για δημιουργία του σχήματος με όλες τις ιδιότητες να έχουν τις προεπιλογές τους. |



### Δείτε επίσης
* κλάση [`IAutoShape`](/slides/python-net/el/aspose.slides/iautoshape)
* κλάση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* απαρίθμηση [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
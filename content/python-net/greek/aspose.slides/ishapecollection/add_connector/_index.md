---
title: add_connector method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Δημιουργεί ένα νέο σχήμα σύνδεσμου με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων.

### Επιστρέφει

Το πρόσφατα δημιουργημένο [`IConnector`](/slides/python-net/el/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) | Το [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) του σχήματος σύνδεσμου προς προσθήκη. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε points. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε points. |
| width | **float** | Το πλάτος του πλαισίου του σύνδεσμου, σε points. |
| height | **float** | Το ύψος του πλαισίου του σύνδεσμου, σε points. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Δημιουργεί ένα νέο σχήμα σύνδεσμου και το προσθέτει στο τέλος της συλλογής σχημάτων, εφαρμόζοντας προαιρετικά το προεπιλεγμένο στυλ προτύπου.

### Επιστρέφει

Το πρόσφατα δημιουργημένο [`IConnector`](/slides/python-net/el/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) | Το [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) του σχήματος σύνδεσμου προς δημιουργία. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε points. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε points. |
| width | **float** | Το πλάτος του πλαισίου του σύνδεσμου, σε points. |
| height | **float** | Το ύψος του πλαισίου του σύνδεσμου, σε points. |
| create_from_template | **bool** | True για εφαρμογή του προεπιλεγμένου στυλ προτύπου (μη κενό όνομα, απλό στυλ); <br/><br/> false για δημιουργία του σύνδεσμου με προεπιλεγμένες τιμές ιδιοτήτων. |



### Δείτε επίσης
* κλάση [`IConnector`](/slides/python-net/el/aspose.slides/iconnector)
* κλάση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* απαρίθμηση [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
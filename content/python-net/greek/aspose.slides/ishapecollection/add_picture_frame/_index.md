---
title: add_picture_frame method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της
            συλλογής σχημάτων.

### Επιστρέφει

Το νεοδημιουργημένο [`IPictureFrame`](/slides/python-net/el/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype) | Καθορίζει τον τύπο σχήματος που περιέχεται στο [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype),<br/><br/>            εκτός από όλα τα είδη γραμμών:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Η συντεταγμένη x του πλαισίου εικόνας, σε points. |
| y | **float** | Η συντεταγμένη y του πλαισίου εικόνας, σε points. |
| width | **float** | Το πλάτος του πλαισίου εικόνας, σε points. |
| height | **float** | Το ύψος του πλαισίου εικόνας, σε points. |
| image | [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) | Το [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) που θα εμφανιστεί στο πλαίσιο εικόνας. |



### Δείτε επίσης
* class [`IPictureFrame`](/slides/python-net/el/aspose.slides/ipictureframe)
* class [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage)
* class [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/el/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/el/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
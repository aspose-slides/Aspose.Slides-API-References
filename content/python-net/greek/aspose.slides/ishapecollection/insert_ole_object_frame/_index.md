---
title: insert_ole_object_frame method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το ενσωματώνει στη συλλογή σχημάτων στο συγκεκριμένο δείκτη.

### Τιμή Επιστροφής

Το νεοδημιουργημένο [`IOleObjectFrame`](/slides/python-net/el/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης στον οποίο θα ενσωματωθεί το πλαίσιο αντικειμένου OLE. |
| x | **float** | Η x-συντεταγμένη του νέου πλαισίου OLE, σε σημεία. |
| y | **float** | Η y-συντεταγμένη του νέου πλαισίου OLE, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo) | Οι ενσωματωμένες πληροφορίες δεδομένων OLE ([`IOleEmbeddedDataInfo`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το ενσωματώνει στη συλλογή σχημάτων στο συγκεκριμένο δείκτη.

### Τιμή Επιστροφής

Το νεοδημιουργημένο [`IOleObjectFrame`](/slides/python-net/el/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης στον οποίο θα ενσωματωθεί το πλαίσιο αντικειμένου OLE. |
| x | **float** | Η x-συντεταγμένη του νέου πλαισίου OLE, σε σημεία. |
| y | **float** | Η y-συντεταγμένη του νέου πλαισίου OLE, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| class_name | **str** | Το όνομα κλάσης του αντικειμένου OLE. |
| path | **str** | Η διαδρομή προς το συνδεδεμένο αρχείο. <br/><br/>Αυτή η διαδρομή αποθηκεύεται κατά λέξη στην παρουσίαση.<br/><br/>Εάν καθοριστεί σχετική διαδρομή, το αρχείο θα είναι μη προσβάσιμο κατά το άνοιγμα<br/><br/>της παρουσίασης από διαφορετικό φάκελο. |



### Δείτε επίσης
* κλάση [`IOleEmbeddedDataInfo`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo)
* κλάση [`IOleObjectFrame`](/slides/python-net/el/aspose.slides/ioleobjectframe)
* κλάση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)
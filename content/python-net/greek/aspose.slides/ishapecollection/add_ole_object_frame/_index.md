---
title: add_ole_object_frame method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων.

### Επιστρέφει

Το νεοδημιουργημένο [`IOleObjectFrame`](/slides/python-net/el/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo) | Οι ενσωματωμένες πληροφορίες δεδομένων OLE ([`IOleEmbeddedDataInfo`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων.

### Επιστρέφει

Το νεοδημιουργημένο [`IOleObjectFrame`](/slides/python-net/el/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| class_name | **str** | Το όνομα κλάσης του αντικειμένου OLE. |
| path | **str** | Η διαδρομή προς το συνδεδεμένο αρχείο. <br/><br/>Αυτή η διαδρομή αποθηκεύεται ακριβώς όπως είναι στην παρουσίαση.<br/><br/>            Εάν καθοριστεί σχετική διαδρομή, το αρχείο θα είναι μη προσβάσιμο όταν ανοίγετε<br/><br/>            την παρουσίαση από διαφορετικό κατάλογο. |



### Δείτε επίσης
* class [`IOleEmbeddedDataInfo`](/slides/python-net/el/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/el/aspose.slides/ioleobjectframe)
* class [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/el/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
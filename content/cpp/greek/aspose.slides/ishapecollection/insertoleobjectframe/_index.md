---
title: InsertOleObjectFrame()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.
type: docs
weight: 79
url: /el/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το πλαίσιο αντικειμένου OLE. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Οι ενσωματωμένες πληροφορίες δεδομένων OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) μέθοδος

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το πλαίσιο αντικειμένου OLE. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| className | [System::String](../../../system/string/) | Το όνομα κλάσης του αντικειμένου OLE. |
| path | [System::String](../../../system/string/) | Η διαδρομή προς το συνδεδεμένο αρχείο. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IOleObjectFrame](../../ioleobjectframe/).

## Σχόλια

Αυτή η διαδρομή αποθηκεύεται ακριβώς στην παρουσίαση. Εάν καθοριστεί σχετική διαδρομή, το αρχείο θα είναι μη προσβάσιμο όταν ανοίγετε την παρουσίαση από διαφορετικό φάκελο.

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IOleObjectFrame](../../ioleobjectframe/)
* Κλάση [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Κλάση [IShapeCollection](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: InsertOleObjectFrame()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.
type: docs
weight: 196
url: /el/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο αντικειμένου OLE. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Οι ενσωματωμένες πληροφορίες δεδομένων OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IOleObjectFrame](../../ioleobjectframe/).

## Σχόλια



Αυτό το παράδειγμα δείχνει την εισαγωγή ενός αντικειμένου OLE στη δεύτερη θέση: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) μέθοδος

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο αντικειμένου OLE. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| className | [System::String](../../../system/string/) | Το όνομα κλάσης του αντικειμένου OLE. |
| path | [System::String](../../../system/string/) | Η διαδρομή προς το συνδεδεμένο αρχείο. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο πλαίσιο αντικειμένου OLE.

## Σχόλια



Αυτή η διαδρομή αποθηκεύεται ακριβώς στην παρουσίαση. Αν καθοριστεί σχετική διαδρομή, το αρχείο θα είναι μη προσβάσιμο όταν ανοίγετε την παρουσίαση από διαφορετικό φάκελο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IOleObjectFrame](../../ioleobjectframe/)
* Κλάση [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Κλάση [ShapeCollection](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
---
title: AddOleObjectFrame()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο πλαίσιο OLE αντικειμένου και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 183
url: /el/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο OLE αντικειμένου και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου OLE, σε μονάδες σημείου. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου OLE, σε μονάδες σημείου. |
| width | **float** | Το πλάτος του νέου πλαισίου OLE, σε μονάδες σημείου. |
| height | **float** | Το ύψος του νέου πλαισίου OLE, σε μονάδες σημείου. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Οι πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Τιμή επιστροφής

Το νεοδημιούργημένο [IOleObjectFrame](../../ioleobjectframe/).

## Σχόλια

Τα παρακάτω παραδείγματα δείχνουν πώς να προσθέσετε Πλαίσια OLE Αντικειμένου στο [Slides](../../) του PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Προσπελαύνει την πρώτη διαφάνεια
auto slide = pres->get_Slides()->idx_get(0);
// Φορτώνει ένα αρχείο Excel σε ροή
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// Δημιουργεί ένα αντικείμενο δεδομένων για ενσωμάτωση
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Προσθέτει ένα σχήμα πλαισίου Ole Object
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// Γράφει το αρχείο PPTX στον δίσκο
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) μέθοδος

Δημιουργεί ένα νέο πλαίσιο OLE αντικειμένου και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου OLE, σε μονάδες σημείου. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου OLE, σε μονάδες σημείου. |
| width | **float** | Το πλάτος του νέου πλαισίου OLE, σε μονάδες σημείου. |
| height | **float** | Το ύψος του νέου πλαισίου OLE, σε μονάδες σημείου. |
| className | [System::String](../../../system/string/) | Το όνομα κλάσης του αντικειμένου OLE. |
| path | [System::String](../../../system/string/) | Η διαδρομή προς το συνδεδεμένο αρχείο. |

### Τιμή επιστροφής

Το νεοδημιούργημένο [IOleObjectFrame](../../ioleobjectframe/).

## Σχόλια

Αυτή η διαδρομή αποθηκεύεται ακριβώς στην παρουσίαση. Εάν καθοριστεί σχετική διαδρομή, το αρχείο θα είναι μη προσβάσιμο κατά το άνοιγμα της παρουσίασης από διαφορετικό φάκελο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IOleObjectFrame](../../ioleobjectframe/)
* Κλάση [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Κλάση [ShapeCollection](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)
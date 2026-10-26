---
title: AddConnector()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο σχήμα συνδέσμου με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 417
url: /el/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) μέθοδος


Δημιουργεί ένα νέο σχήμα συνδέσμου με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του σχήματος συνδέσμου για προσθήκη. |
| x | **float** | Η συντεταγμένη x του πλαισίου του συνδέσμου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του συνδέσμου, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του συνδέσμου, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του συνδέσμου, σε σημεία. |

### Return Value

Το νεοδημιουργημένο [IConnector](../../iconnector/).

## Σχόλια



Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε έναν σύνδεσμο (έναν λυγισμένο σύνδεσμο) μεταξύ δύο σχημάτων (ένα ελλειπτικό σχήμα και ένα ορθογώνιο) στο PowerPoint [Presentation](../../presentation/). 
```cpp
// Δημιουργεί μια κλάση παρουσίασης που αντιπροσωπεύει αρχείο PPTX
auto input = System::MakeObject<Presentation>();

// Προσπελαεύει τη συλλογή σχημάτων για μια συγκεκριμένη διαφάνεια
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Προσθέτει ένα αυτόματο σχήμα Έλλειψη
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Προσθέτει ένα αυτόματο σχήμα Ορθογώνιο
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Προσθέτει ένα σχήμα συνδέσμου στη συλλογή σχημάτων της διαφάνειας
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Συνδέει τα σχήματα χρησιμοποιώντας το σύνδεσμο
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Καλεί τη μέθοδο reroute που ορίζει την αυτόματη συντομότερη διαδρομή μεταξύ των σχημάτων
connector->Reroute();

// Αποθηκεύει την παρουσίαση
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) μέθοδος


Δημιουργεί ένα νέο σχήμα συνδέσμου και το προσθέτει στο τέλος της συλλογής σχημάτων, εφαρμόζοντας προαιρετικά το προεπιλεγμένο στυλ προτύπου.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του σχήματος συνδέσμου για δημιουργία. |
| x | **float** | Η συντεταγμένη x του πλαισίου του συνδέσμου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του συνδέσμου, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του συνδέσμου, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του συνδέσμου, σε σημεία. |
| createFromTemplate | **bool** | Αληθές για εφαρμογή προεπιλεγμένου στυλ προτύπου (μη κενό όνομα, απλό στυλ); ψευδές για δημιουργία του συνδέσμου με προεπιλεγμένες τιμές ιδιοτήτων. |

### Return Value

Το νεοδημιουργημένο [IConnector](../../iconnector/).

## Δείτε επίσης

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
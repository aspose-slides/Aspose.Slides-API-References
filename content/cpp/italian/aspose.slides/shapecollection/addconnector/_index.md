---
title: AddConnector()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova forma connettore con lo stile di modello predefinito e la aggiunge alla fine della raccolta di forme.
type: docs
weight: 417
url: /it/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) metodo


Crea una nuova forma connettore con lo stile di modello predefinito e la aggiunge alla fine della raccolta di forme.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma connettore da aggiungere. |
| x | **float** | La coordinata x del frame del connettore, in punti. |
| y | **float** | La coordinata y del frame del connettore, in punti. |
| width | **float** | La larghezza del frame del connettore, in punti. |
| height | **float** | L’altezza del frame del connettore, in punti. |

### Valore di ritorno

La [IConnector](../../iconnector/) appena creata.
## Note



Il seguente esempio mostra come aggiungere un connettore (un connettore curvo) tra due forme (un'ellisse e un rettangolo) in PowerPoint [Presentation](../../presentation/). 
```cpp
// Istanzia una classe di presentazione che rappresenta un file PPTX
auto input = System::MakeObject<Presentation>();

// Accede alla raccolta di forme per una diapositiva specifica
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Aggiunge una forma automatica Ellisse
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Aggiunge una forma automatica Rettangolo
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Aggiunge una forma connettore alla raccolta di forme della diapositiva
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Collega le forme usando il connettore
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Chiama reroute che imposta il percorso più breve automatico tra le forme
connector->Reroute();

// Salva la presentazione
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) metodo


Crea una nuova forma connettore e la aggiunge alla fine della raccolta di forme, applicando facoltativamente lo stile di modello predefinito.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Il [ShapeType](../../shapetype/) della forma connettore da creare. |
| x | **float** | La coordinata x del frame del connettore, in punti. |
| y | **float** | La coordinata y del frame del connettore, in punti. |
| width | **float** | La larghezza del frame del connettore, in punti. |
| height | **float** | L’altezza del frame del connettore, in punti. |
| createFromTemplate | **bool** | True per applicare lo stile di modello predefinito (nome non vuoto, stile semplice); false per creare il connettore con i valori predefiniti delle proprietà. |

### Valore di ritorno

La [IConnector](../../iconnector/) appena creata.

## Vedi anche

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IConnector](../../iconnector/)
* Classe [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)
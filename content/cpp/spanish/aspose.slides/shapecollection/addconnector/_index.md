---
title: AddConnector()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva forma de conector con el estilo de plantilla predeterminado y la agrega al final de la colección de formas.
type: docs
weight: 417
url: /es/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) método

Crea una nueva forma de conector con el estilo de plantilla predeterminado y la agrega al final de la colección de formas.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma de conector a agregar. |
| x | **float** | La coordenada x del marco del conector, en puntos. |
| y | **float** | La coordenada y del marco del conector, en puntos. |
| width | **float** | El ancho del marco del conector, en puntos. |
| height | **float** | La altura del marco del conector, en puntos. |

### Valor devuelto

El [IConnector](../../iconnector/) recién creado.

## Observaciones

El siguiente ejemplo muestra cómo agregar un conector (un conector curvo) entre dos formas (una elipse y un rectángulo) en PowerPoint [Presentation](../../presentation/). 
```cpp
// Instancia una clase de presentación que representa un archivo PPTX
auto input = System::MakeObject<Presentation>();

// Accede a la colección de formas de una diapositiva específica
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Agrega una forma automática Elipse
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Agrega una forma automática Rectángulo
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Agrega una forma de conector a la colección de formas de la diapositiva
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Conecta las formas usando el conector
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Llama a Reroute que establece la ruta más corta automática entre las formas
connector->Reroute();

// Guarda la presentación
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) método

Crea una nueva forma de conector y la agrega al final de la colección de formas, aplicando opcionalmente el estilo de plantilla predeterminado.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | El [ShapeType](../../shapetype/) de la forma de conector a crear. |
| x | **float** | La coordenada x del marco del conector, en puntos. |
| y | **float** | La coordenada y del marco del conector, en puntos. |
| width | **float** | El ancho del marco del conector, en puntos. |
| height | **float** | La altura del marco del conector, en puntos. |
| createFromTemplate | **bool** | True para aplicar el estilo de plantilla predeterminado (nombre no vacío, estilo simple); false para crear el conector con los valores predeterminados de sus propiedades. |

### Valor devuelto

El [IConnector](../../iconnector/) recién creado.

## Ver también

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
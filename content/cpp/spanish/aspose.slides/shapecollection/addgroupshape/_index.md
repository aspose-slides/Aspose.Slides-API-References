---
title: AddGroupShape()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva forma de grupo vacía y la agrega al final de la colección de formas. El marco del grupo\u2019s se ajustará automáticamente para encajar cualquier forma añadida.
type: docs
weight: 391
url: /es/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() método

Crea una nueva forma de grupo vacía y la agrega al final de la colección de formas. El marco del grupo se ajustará automáticamente para encajar cualquier forma añadida.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### Valor de retorno

El [IGroupShape](../../igroupshape/) recién creado.

## Observaciones

El siguiente ejemplo muestra cómo agregar una forma de grupo a una diapositiva de PowerPoint [Presentation](../../presentation/).

```cpp
// Instanciar la clase Presentation
auto pres = System::MakeObject<Presentation>();

// Obtener la primera diapositiva
auto slide = pres->get_Slides()->idx_get(0);
// Accediendo a la colección de formas de las diapositivas
auto slideShapes = slide->get_Shapes();
// Añadiendo una forma de grupo a la diapositiva
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Añadiendo formas dentro de la forma de grupo añadida
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Añadiendo el marco de la forma de grupo
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Escribir el archivo PPTX en disco
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) método

Crea una nueva forma de grupo, convierte la imagen SVG especificada en formas individuales y agrega el grupo resultante al final de la colección de formas.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | El [ISvgImage](../../isvgimage/) que contiene contenido vectorial para convertir en formas. |
| x | **float** | La coordenada x del marco del grupo, en puntos. |
| y | **float** | La coordenada y del marco del grupo, en puntos. |
| width | **float** | El ancho del marco del grupo, en puntos. |
| height | **float** | El alto del marco del grupo, en puntos. |

### Valor de retorno

El [IGroupShape](../../igroupshape/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IGroupShape](../../igroupshape/)
* Clase [ShapeCollection](../)
* Clase [ISvgImage](../../isvgimage/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
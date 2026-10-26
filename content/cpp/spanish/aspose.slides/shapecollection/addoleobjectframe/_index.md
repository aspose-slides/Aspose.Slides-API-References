---
title: AddOleObjectFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas.
type: docs
weight: 183
url: /es/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) método


Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco OLE, en puntos. |
| y | **float** | La coordenada y del nuevo marco OLE, en puntos. |
| width | **float** | El ancho del nuevo marco OLE, en puntos. |
| height | **float** | La altura del nuevo marco OLE, en puntos. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | La información sobre los datos OLE incrustados ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valor devuelto

El [IOleObjectFrame](../../ioleobjectframe/) recién creado.
## Observaciones



El siguiente ejemplo muestra cómo agregar marcos de objeto OLE a [Slides](../../) de PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Accede a la primera diapositiva
auto slide = pres->get_Slides()->idx_get(0);
// Carga un archivo excel en un flujo
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

// Crea un objeto de datos para incrustar
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Agrega una forma de marco de objeto Ole
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
//Escribe el archivo PPTX en disco
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) método


Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco OLE, en puntos. |
| y | **float** | La coordenada y del nuevo marco OLE, en puntos. |
| width | **float** | El ancho del nuevo marco OLE, en puntos. |
| height | **float** | La altura del nuevo marco OLE, en puntos. |
| className | [System::String](../../../system/string/) | El nombre de clase del objeto OLE. |
| path | [System::String](../../../system/string/) | La ruta al archivo vinculado. |

### Valor devuelto

El [IOleObjectFrame](../../ioleobjectframe/) recién creado.
## Observaciones



Esta ruta se almacena literalmente en la presentación. Si se especifica una ruta relativa, el archivo será inaccesible al abrir la presentación desde un directorio diferente.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
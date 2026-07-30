---
title: AddOleObjectFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo frame di oggetto OLE e lo aggiunge alla fine della raccolta di forme.
type: docs
weight: 183
url: /it/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metodo


Crea un nuovo frame di oggetto OLE e lo aggiunge alla fine della raccolta di forme.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Le informazioni sui dati OLE incorporati ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valore di ritorno

Il [IOleObjectFrame](../../ioleobjectframe/) appena creato.

## Osservazioni



Il seguente esempio mostra come aggiungere frame di oggetti OLE a [Slides](../../) di PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Accede alla prima diapositiva
auto slide = pres->get_Slides()->idx_get(0);
// Carica un file Excel in uno stream
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

// Crea un oggetto dati per l'incorporamento
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Aggiunge una forma Ole Object Frame
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// Scrive il file PPTX su disco
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) metodo


Crea un nuovo frame di oggetto OLE e lo aggiunge alla fine della raccolta di forme.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| className | [System::String](../../../system/string/) | Il nome della classe dell'oggetto OLE. |
| path | [System::String](../../../system/string/) | Il percorso al file collegato. |

### Valore di ritorno

Il [IOleObjectFrame](../../ioleobjectframe/) appena creato.

## Osservazioni



Questo percorso viene memorizzato così com'è nella presentazione. Se viene specificato un percorso relativo, il file sarà inaccessibile quando si apre la presentazione da una directory diversa.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [ShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
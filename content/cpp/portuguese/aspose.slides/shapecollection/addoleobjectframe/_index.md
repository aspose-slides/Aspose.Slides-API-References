---
title: AddOleObjectFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.
type: docs
weight: 183
url: /pt/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) método


Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | As informações sobre os dados OLE incorporados ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valor de Retorno

O [IOleObjectFrame](../../ioleobjectframe/) recém-criado.

## Observações



O exemplo a seguir mostra como adicionar quadros de objeto OLE a [Slides](../../) do PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Acessa o primeiro slide
auto slide = pres->get_Slides()->idx_get(0);
// Carrega um arquivo Excel para o fluxo
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

// Cria um objeto de dados para incorporação
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Adiciona uma forma de quadro de objeto OLE
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// Grava o arquivo PPTX no disco
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) método


Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro OLE, em pontos. |
| y | **float** | A coordenada y do novo quadro OLE, em pontos. |
| width | **float** | A largura do novo quadro OLE, em pontos. |
| height | **float** | A altura do novo quadro OLE, em pontos. |
| className | [System::String](../../../system/string/) | O nome da classe do objeto OLE. |
| path | [System::String](../../../system/string/) | O caminho para o arquivo vinculado. |

### Valor de Retorno

O [IOleObjectFrame](../../ioleobjectframe/) recém-criado.

## Observações



Este caminho é armazenado literalmente na apresentação. Se um caminho relativo for especificado, o arquivo ficará inacessível ao abrir a apresentação a partir de um diretório diferente.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleObjectFrame](../../ioleobjectframe/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [ShapeCollection](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
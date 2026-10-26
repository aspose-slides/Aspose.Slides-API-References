---
title: InsertSectionZoomFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de Zoom de Seção e o insere na coleção de formas no índice especificado.
type: docs
weight: 131
url: /pt/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) método


Cria um novo quadro de Zoom [Section](../../section/) e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o quadro de Zoom [Section](../../section/). |
| x | **float** | A coordenada x do novo quadro de Zoom [Section](../../section/), em pontos. |
| y | **float** | A coordenada y do novo quadro de Zoom [Section](../../section/), em pontos. |
| width | **float** | A largura do novo quadro de Zoom [Section](../../section/), em pontos. |
| height | **float** | A altura do novo quadro de Zoom [Section](../../section/), em pontos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | O [ISection](../../isection/) referenciado pelo quadro de Zoom [Section](../../section/); deve pertencer a esta apresentação e conter pelo menos um slide. |

### Valor de Retorno

O [ISectionZoomFrame](../../isectionzoomframe/) recém-criado.

## Observações


Este exemplo demonstra a criação e inserção de um objeto Zoom [Section](../../section/) no índice especificado de uma coleção (suponha que existam pelo menos duas seções na apresentação "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) método


Cria um novo quadro de Zoom [Section](../../section/) com uma imagem predefinida e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o quadro de Zoom [Section](../../section/). |
| x | **float** | A coordenada x do novo quadro de Zoom [Section](../../section/), em pontos. |
| y | **float** | A coordenada y do novo quadro de Zoom [Section](../../section/), em pontos. |
| width | **float** | A largura do novo quadro de Zoom [Section](../../section/), em pontos. |
| height | **float** | A altura do novo quadro de Zoom [Section](../../section/), em pontos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | O [ISection](../../isection/) referenciado pelo quadro de Zoom [Section](../../section/); deve pertencer a esta apresentação e conter pelo menos um slide. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A imagem a ser exibida dentro do quadro de Zoom [Section](../../section/). |

### Valor de Retorno

O [ISectionZoomFrame](../../isectionzoomframe/) recém-criado.

## Observações


Este exemplo demonstra a criação e inserção de um objeto Zoom [Section](../../section/) no índice especificado de uma coleção (suponha que existam pelo menos duas seções na apresentação "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISectionZoomFrame](../../isectionzoomframe/)
* Classe [ISection](../../isection/)
* Classe [IShapeCollection](../)
* Classe [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
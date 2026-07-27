---
title: AddSectionZoomFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de Zoom de Seção e o adiciona ao final da coleção de formas.
type: docs
weight: 118
url: /pt/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) método


Cria um novo [Section](../../section/) Zoom frame e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | A coordenada x do novo [Section](../../section/) Zoom frame, em pontos. |
| y | **float** | A coordenada y do novo [Section](../../section/) Zoom frame, em pontos. |
| width | **float** | A largura do novo [Section](../../section/) Zoom frame, em pontos. |
| height | **float** | A altura do novo [Section](../../section/) Zoom frame, em pontos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | O [ISection](../../isection/) referenciado pelo [Section](../../section/) Zoom frame; deve pertencer a esta apresentação e conter ao menos um slide. |

### Valor de Retorno

O [ISectionZoomFrame](../../isectionzoomframe/) recém-criado.

## Observações


Este exemplo demonstra como adicionar um [Section](../../section/) Zoom object ao final de uma coleção (presuma que existam ao menos duas seções na apresentação \"Presentation.pptx\"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) método


Cria um novo [Section](../../section/) Zoom frame com uma imagem predefinida e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | A coordenada x do novo [Section](../../section/) Zoom frame, em pontos. |
| y | **float** | A coordenada y do novo [Section](../../section/) Zoom frame, em pontos. |
| width | **float** | A largura do novo [Section](../../section/) Zoom frame, em pontos. |
| height | **float** | A altura do novo [Section](../../section/) Zoom frame, em pontos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | O [ISection](../../isection/) referenciado pelo [Section](../../section/) Zoom frame; deve pertencer a esta apresentação e conter ao menos um slide. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | O [IPPImage](../../ippimage/) a ser exibido dentro do [Section](../../section/) Zoom frame. |

### Valor de Retorno

O [ISectionZoomFrame](../../isectionzoomframe/) recém-criado.

## Observações


Este exemplo demonstra como adicionar um [Section](../../section/) Zoom object ao final de uma coleção (presuma que existam ao menos duas seções na apresentação \"Presentation.pptx\"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
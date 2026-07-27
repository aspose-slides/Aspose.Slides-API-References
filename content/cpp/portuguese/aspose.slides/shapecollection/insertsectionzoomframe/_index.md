---
title: InsertSectionZoomFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo frame Section Zoom e o insere na coleção de shapes no índice especificado.
type: docs
weight: 144
url: /pt/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method


Cria um novo [Section](../../section/) Zoom frame e o insere na coleção de shapes no índice especificado.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o [Section](../../section/) Zoom frame. |
| x | **float** | A coordenada x do novo [Section](../../section/) Zoom frame, em points. |
| y | **float** | A coordenada y do novo [Section](../../section/) Zoom frame, em points. |
| width | **float** | A largura do novo [Section](../../section/) Zoom frame, em points. |
| height | **float** | A altura do novo [Section](../../section/) Zoom frame, em points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | O [ISection](../../isection/) referenciado pelo [Section](../../section/) Zoom frame; deve pertencer a esta apresentação e conter ao menos um slide. |

### Valor de Retorno

O [ISectionZoomFrame](../../isectionzoomframe/) recém-criado.
## Observações


Este exemplo demonstra a criação e inserção de um objeto Zoom [Section](../../section/) no índice especificado de uma coleção (suponha que existam ao menos duas seções na apresentação "Presentation.pptx"):. 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method


Cria um novo [Section](../../section/) Zoom frame com uma imagem predefinida e o insere na coleção de shapes no índice especificado.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o [Section](../../section/) Zoom frame. |
| x | **float** | A coordenada x do novo [Section](../../section/) Zoom frame, em points. |
| y | **float** | A coordenada y do novo [Section](../../section/) Zoom frame, em points. |
| width | **float** | A largura do novo [Section](../../section/) Zoom frame, em points. |
| height | **float** | A altura do novo [Section](../../section/) Zoom frame, em points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | O [ISection](../../isection/) referenciado pelo [Section](../../section/) Zoom frame; deve pertencer a esta apresentação e conter ao menos um slide. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A imagem a ser exibida dentro do [Section](../../section/) Zoom frame. |

### Valor de Retorno

O [ISectionZoomFrame](../../isectionzoomframe/) recém-criado.
## Observações


Este exemplo demonstra a criação e inserção de um objeto Zoom [Section](../../section/) no índice especificado de uma coleção (suponha que existam ao menos duas seções na apresentação "Presentation.pptx"):. 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
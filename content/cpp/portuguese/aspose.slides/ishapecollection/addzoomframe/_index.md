---
title: AddZoomFrame()
second_title: Aspose.Slides para C++ Referência da API
description: Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas.
type: docs
weight: 92
url: /pt/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) método

Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro de Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro de Zoom, em pontos. |
| width | **float** | A largura do novo quadro de Zoom, em pontos. |
| height | **float** | A altura do novo quadro de Zoom, em pontos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | O [ISlide](../../islide/) referenciado pelo quadro de Zoom; deve pertencer a esta apresentação. |

### Valor de Retorno

O [IZoomFrame](../../izoomframe/) recém-criado.

## Observações

Este exemplo demonstra a adição de um objeto Zoom ao final de uma coleção (presuma que existam pelo menos dois slides na apresentação "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) método

Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro de Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro de Zoom, em pontos. |
| width | **float** | A largura do novo quadro de Zoom, em pontos. |
| height | **float** | A altura do novo quadro de Zoom, em pontos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | O [ISlide](../../islide/) referenciado pelo quadro de Zoom; deve pertencer a esta apresentação. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A imagem para o slide referenciado [IPPImage](../../ippimage/). |

### Valor de Retorno

O [IZoomFrame](../../izoomframe/) recém-criado.

## Observações

Este exemplo demonstra a adição de um objeto Zoom ao final de uma coleção (presuma que existam pelo menos dois slides na apresentação "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
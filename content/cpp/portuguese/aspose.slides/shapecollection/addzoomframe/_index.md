---
title: AddZoomFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro Zoom e o adiciona ao final da coleção de formas.
type: docs
weight: 105
url: /pt/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) método

Cria um novo quadro Zoom e o adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro Zoom, em pontos. |
| width | **float** | A largura do novo quadro Zoom, em pontos. |
| height | **float** | A altura do novo quadro Zoom, em pontos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | O [ISlide](../../islide/) referenciado pelo quadro Zoom; deve pertencer a esta apresentação. |

### Valor de Retorno

O [IZoomFrame](../../izoomframe/) recém-criado.

## Observações

Este exemplo demonstra a adição de um objeto Zoom ao final de uma coleção (suponha que existam pelo menos dois slides na apresentação "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) método

Cria um novo quadro Zoom e o adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro Zoom, em pontos. |
| width | **float** | A largura do novo quadro Zoom, em pontos. |
| height | **float** | A altura do novo quadro Zoom, em pontos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | O [ISlide](../../islide/) referenciado pelo quadro Zoom; deve pertencer a esta apresentação. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A imagem para o slide referenciado [IPPImage](../../ippimage/). |

### Valor de Retorno

O [IZoomFrame](../../izoomframe/) recém-criado.

## Observações

Este exemplo demonstra a adição de um objeto Zoom ao final de uma coleção (suponha que existam pelo menos dois slides na apresentação "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IZoomFrame](../../izoomframe/)
* Classe [ISlide](../../islide/)
* Classe [ShapeCollection](../)
* Classe [IPPImage](../../ippimage/)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
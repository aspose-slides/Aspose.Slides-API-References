---
title: InsertZoomFrame()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de Zoom e o insere na coleção de formas no índice especificado.
type: docs
weight: 105
url: /pt/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) method

Cria um novo quadro de Zoom e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero onde o quadro de Zoom será inserido. |
| x | **float** | A coordenada x do novo quadro de Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro de Zoom, em pontos. |
| width | **float** | A largura do novo quadro de Zoom, em pontos. |
| height | **float** | A altura do novo quadro de Zoom, em pontos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | O [ISlide](../../islide/) referenciado pelo quadro de Zoom. |

### Valor de Retorno

O [IZoomFrame](../../izoomframe/) recém-criado.

## Observações

Este exemplo demonstra a criação e inserção de um objeto Zoom no índice especificado de uma coleção (assuma que haja pelo menos dois slides na apresentação "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Cria um novo quadro de Zoom com uma imagem pré-definida e o insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero onde o quadro de Zoom será inserido. |
| x | **float** | A coordenada x do novo quadro de Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro de Zoom, em pontos. |
| width | **float** | A largura do novo quadro de Zoom, em pontos. |
| height | **float** | A altura do novo quadro de Zoom, em pontos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | O [ISlide](../../islide/) referenciado pelo quadro de Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | A imagem para o slide referenciado [IPPImage](../../ippimage/). |

### Valor de Retorno

O [IZoomFrame](../../izoomframe/) recém-criado.

## Observações

Este exemplo demonstra a criação e inserção de um objeto Zoom no índice especificado de uma coleção (assuma que haja pelo menos dois slides na apresentação "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IZoomFrame](../../izoomframe/)
* Classe [ISlide](../../islide/)
* Classe [IShapeCollection](../)
* Classe [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
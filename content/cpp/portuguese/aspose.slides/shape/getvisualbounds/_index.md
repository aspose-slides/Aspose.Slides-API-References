---
title: GetVisualBounds()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado.
type: docs
weight: 677
url: /pt/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() método


Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```


### Valor de Retorno

Um [System::Drawing::RectangleF](../../../system.drawing/rectanglef/) que representa os limites visuais da forma em coordenadas do slide.
## Observações


O retângulo retornado representa os limites alinhados aos eixos de todo o conteúdo produzido pela forma durante a renderização no espaço de coordenadas do slide.

Esses limites podem diferir dos limites do modelo da forma ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) e podem conter coordenadas negativas se o conteúdo renderizado se estender além da origem do slide.

Os limites visuais levam em conta aspectos relacionados à renderização, como transformações (por exemplo, rotação), largura e junções de traçado, layout e transbordamento de texto, [SmartArt](../../../aspose.slides.smartart/) geometria, e outros efeitos de layout que influenciam a aparência final renderizada da forma.

Os limites retornados não são recortados ao retângulo do slide. 

## Veja Também

* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [Shape](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)
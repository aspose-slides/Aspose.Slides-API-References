---
title: BeginContainer()
second_title: Referência da API Aspose.Slides para C++
description: Salva um contêiner com o estado atual deste objeto, abre e usa um novo contêiner e devolve o contêiner salvo.
type: docs
weight: 976
url: /pt/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() método

Salva um contêiner com o estado atual deste objeto, abre e usa um novo contêiner e devolve o contêiner salvo.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) método

Salva um contêiner com o estado atual deste objeto, abre e usa um novo contêiner e devolve o contêiner salvo.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | O retângulo que especifica uma transformação de escala do novo contêiner. Usado junto com **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | O retângulo que especifica uma transformação de escala do novo contêiner. Usado junto com **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | O valor que especifica a unidade de medida do novo contêiner |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) método

Salva um contêiner com o estado atual deste objeto, abre e usa um novo contêiner e devolve o contêiner salvo.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | O retângulo que especifica uma transformação de escala do novo contêiner. Usado junto com **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | O retângulo que especifica uma transformação de escala do novo contêiner. Usado junto com **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | O valor que especifica a unidade de medida do novo contêiner |

## Veja Também

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Classe [RectangleF](../../rectanglef/)
* Espaço de nomes [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
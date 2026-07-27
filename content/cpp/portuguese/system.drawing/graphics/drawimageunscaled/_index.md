---
title: DrawImageUnscaled()
second_title: Referência da API Aspose.Slides para C++
description: Desenha a imagem especificada usando seu tamanho físico original na localização especificada.
type: docs
weight: 443
url: /pt/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) método

Desenha a imagem especificada usando seu tamanho físico original na localização especificada.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| x | int | A coordenada X do canto superior esquerdo da imagem desenhada |
| y | int | A coordenada Y do canto superior esquerdo da imagem desenhada |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) método

Desenha uma imagem especificada usando seu tamanho físico original em uma localização especificada.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| x | int | A coordenada X do canto superior esquerdo da imagem desenhada |
| y | int | A coordenada Y do canto superior esquerdo da imagem desenhada |
| width | int | Não usado |
| height | int | Não usado |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) método

Desenha uma imagem especificada usando seu tamanho físico original em uma localização especificada.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| rect | const [Rectangle](../../rectangle/)\& | O Rectangle que especifica o canto superior esquerdo da imagem desenhada. As propriedades X e Y do Rectangle especificam o canto superior esquerdo. Os valores de width e height são ignorados. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) método

Desenha uma imagem especificada usando seu tamanho físico original em uma localização especificada.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A imagem a ser desenhada |
| point | const [Point](../../point/)\& | A estrutura [Point](../../point/) que especifica o canto superior esquerdo da imagem desenhada. |

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [Point](../../point/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
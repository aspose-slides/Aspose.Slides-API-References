---
title: DrawString()
second_title: Referência da API Aspose.Slides para C++
description: Desenha a string especificada na localização especificada usando a fonte e o pincel especificados.
type: docs
weight: 365
url: /pt/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) método

Desenha a string especificada na localização especificada usando a fonte e o pincel especificados.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | A string a ser desenhada |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Uma fonte a ser usada |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Um objeto [Brush](../../brush/) a ser usado para desenhar |
| topLeft | [PointF](../../pointf/) | Especifica a localização do canto superior esquerdo da string desenhada |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Especifica o formato da string |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) método

Desenha a string especificada no retângulo especificado usando a fonte e o pincel especificados.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | A string a ser desenhada |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Uma fonte a ser usada |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Um objeto [Brush](../../brush/) a ser usado para desenhar |
| layoutRectangle | [RectangleF](../../rectanglef/) | Especifica um retângulo no qual desenhar a string |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Especifica o formato da string |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) método

Desenha a string especificada na localização especificada usando a fonte e o pincel especificados.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | A string a ser desenhada |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Uma fonte a ser usada |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Um objeto [Brush](../../brush/) a ser usado para desenhar |
| x | **float** | A coordenada X da localização do canto superior esquerdo da string desenhada |
| y | **float** | A coordenada Y da localização do canto superior esquerdo da string desenhada |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Especifica o formato da string |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Font](../../font/)
* Classe [Brush](../../brush/)
* Classe [PointF](../../pointf/)
* Classe [StringFormat](../../stringformat/)
* Classe [Graphics](../)
* Classe [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
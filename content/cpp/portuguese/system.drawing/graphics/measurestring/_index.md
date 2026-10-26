---
title: MeasureString()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o tamanho da string especificada quando desenhada na fonte especificada no formato especificado.
type: docs
weight: 521
url: /pt/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, PointF const&, System::SharedPtr\<StringFormat\> const&) const method

Retorna o tamanho da string especificada quando desenhada na fonte especificada no formato especificado.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | A string cujo tamanho será calculado |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | A fonte usada para desenhar a string |
| origin | [PointF](../../pointf/) const\& | Especifica a localização do canto superior esquerdo da string |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Especifica o formato da string |

### Valor de Retorno

Um objeto [SizeF](../../sizef/) que representa o tamanho da string nas unidades de medida especificadas pela propriedade PageUnit do objeto Grapphics atual.

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, int, System::SharedPtr\<StringFormat\> const&) const method

Retorna o tamanho da string especificada quando desenhada na fonte especificada no formato especificado.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | A string cujo tamanho será calculado |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | A fonte usada para desenhar a string |
| width | int | A largura máxima da string |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Especifica o formato da string |

### Valor de Retorno

Um objeto [SizeF](../../sizef/) que representa o tamanho da string nas unidades de medida especificadas pela propriedade PageUnit do objeto Grapphics atual.

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, SizeF const&, System::SharedPtr\<StringFormat\> const&, int\&, int\&) const method

NÃO IMPLEMENTADO.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, SizeF const&, System::SharedPtr\<StringFormat\> const&) const method

Retorna o tamanho da string especificada quando desenhada na fonte especificada no formato especificado.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | A string cujo tamanho será calculado |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | A fonte usada para desenhar a string |
| layoutArea | [SizeF](../../sizef/) const\& | A área máxima de layout da string |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Especifica o formato da string |

### Valor de Retorno

Um objeto [SizeF](../../sizef/) que representa o tamanho da string nas unidades de medida especificadas pela propriedade PageUnit do objeto Grapphics atual.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SizeF](../../sizef/)
* Classe [String](../../../system/string/)
* Classe [Font](../../font/)
* Classe [PointF](../../pointf/)
* Classe [StringFormat](../../stringformat/)
* Classe [Graphics](../)
* Espaço de nomes [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)
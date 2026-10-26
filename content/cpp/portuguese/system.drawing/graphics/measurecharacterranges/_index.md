---
title: MeasureCharacterRanges()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um array de regiões, cada uma delimitando posições de caracteres na string especificada.
type: docs
weight: 508
url: /pt/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) method


Retorna um array de regiões, cada uma delimitando posições de caracteres na string especificada.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | A string a ser medida |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | A fonte usada durante a medição da string |
| layoutRect | [RectangleF](../../rectanglef/) | O retângulo de layout usado durante a medição da string |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | O formato de string, contendo os intervalos de caracteres a medir |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Region](../../region/)
* Classe [String](../../../system/string/)
* Classe [Font](../../font/)
* Classe [RectangleF](../../rectanglef/)
* Classe [StringFormat](../../stringformat/)
* Classe [Graphics](../)
* Namespace [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)
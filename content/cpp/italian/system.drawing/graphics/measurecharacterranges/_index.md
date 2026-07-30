---
title: MeasureCharacterRanges()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un array di regioni, ognuna delle quali delimita le posizioni dei caratteri nella stringa specificata.
type: docs
weight: 508
url: /it/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String&, const SharedPtr<Font>&, RectangleF, const SharedPtr<StringFormat>&) metodo

Restituisce una matrice di regioni, ognuna delle quali delimita le posizioni dei caratteri nella stringa specificata.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | The string to measure |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | The font used during the measurement of the string |
| layoutRect | [RectangleF](../../rectanglef/) | The layout rectangle used during the measurement of the string |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | The string format, contaions the character ranges to measure |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Region](../../region/)
* Classe [String](../../../system/string/)
* Classe [Font](../../font/)
* Classe [RectangleF](../../rectanglef/)
* Classe [StringFormat](../../stringformat/)
* Classe [Graphics](../)
* Spazio dei nomi [System::Drawing](../../)
* Libreria [Aspose.Slides](../../../)
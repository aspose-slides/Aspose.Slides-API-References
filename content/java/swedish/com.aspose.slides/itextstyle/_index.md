---
title: ITextStyle
second_title: Aspose.Slides for Java API-referens
description: Egenskaper för textstilformatering.
type: docs
url: /sv/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Egenskaper för textstilformatering.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Om en stilnivå finns returneras den, annars returneras null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Standardparagrafsegenskaper. |
| [getEffective()](#getEffective--) | Hämtar effektiv textstilformateringsdata med arv tillämpat. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Om en stilnivå finns returneras den, annars returneras null.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index för nivån. Måste ligga i intervallet 0..8. |

**Returnerar:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatering av nivå [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Standardparagrafsegenskaper. skrivskyddad [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returnerar:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Hämtar effektiv textstilformateringsdata med arv tillämpat.

**Returnerar:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - En [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).
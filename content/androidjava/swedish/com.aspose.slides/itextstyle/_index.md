---
title: ITextStyle
second_title: Aspose.Slides för Android via Java API-referens
description: Formateringsegenskaper för textstil.
type: docs
url: /sv/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Text style formatting properties.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Om stilnivån finns returneras den, annars returneras null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Standardparagrafsegenskaper. |
| [getEffective()](#getEffective--) | Hämtar effektiv textstilformateringsdata med ärftlighet tillämpad. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Om stilnivån finns returneras den, annars returneras null.

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

Standardparagrafsegenskaper. Skrivskyddad [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returnerar:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Hämtar effektiv textstilformateringsdata med ärftlighet tillämpad.

**Returnerar:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - En [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).
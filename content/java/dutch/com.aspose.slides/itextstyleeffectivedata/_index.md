---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Onveranderlijk object dat effectieve tekstopmaak-eigenschappen bevat.
type: docs
url: /nl/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Onveranderlijk object dat effectieve tekstopmaak-eigenschappen bevat.

--------------------

Deze interface wordt samen met de [ITextStyle](../../com.aspose.slides/itextstyle) interface gebruikt om effectieve opmaakwaarden met overerving toe te passen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Returns level of effective style. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Returns effective default paragraph properties. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Retourneert het niveau van de effectieve stijl.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Nul-gebaseerde index van het niveau. Must lay in 0..8 interval. |

**Retour:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Effectieve opmaak van niveau [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Retourneert effectieve standaard paragraafeigenschappen. Alleen-lezen [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Retour:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)
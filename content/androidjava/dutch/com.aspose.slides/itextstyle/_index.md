---
title: ITextStyle
second_title: Aspose.Slides voor Android via Java API-referentie
description: Eigenschappen voor tekststijlopmaak.
type: docs
url: /nl/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Eigenschappen voor tekststijlopmaak.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Als het niveau van de stijl bestaat, retourneert het dat, anders retourneert het null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Standaard alinea-eigenschappen. |
| [getEffective()](#getEffective--) | Haalt de effectieve tekststijlopmaakgegevens op met de toegepaste overerving. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Als het niveau van de stijl bestaat, retourneert het dat, anders retourneert het null.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Nulgebaseerde index van het niveau. Moet liggen in het interval 0..8. |

**Retourwaarde:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Opmaak van niveau [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Standaard alinea-eigenschappen. Alleen-lezen [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retourwaarde:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Haalt de effectieve tekststijlopmaakgegevens op met de toegepaste overerving.

**Retourwaarde:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Een [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).
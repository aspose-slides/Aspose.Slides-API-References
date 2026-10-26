---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
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
| [getLevel(int index)](#getLevel-int-) | Als het niveau van de stijl bestaat, retourneert het dit, anders retourneert het null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Standaard paragraaf-eigenschappen. |
| [getEffective()](#getEffective--) | Haalt effectieve tekststijl-opmaakgegevens op met de toegepaste overerving. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```


Als het niveau van de stijl bestaat, retourneert het dit, anders retourneert het null.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Nulgebaseerde index van het niveau. Moet liggen in het interval 0..8. |

**Retour:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Opmaak van niveau [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```


Standaard paragraaf-eigenschappen. Alleen-lezen [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retour:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```


Haalt effectieve tekststijl-opmaakgegevens op met de toegepaste overerving.

**Retour:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Een [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).
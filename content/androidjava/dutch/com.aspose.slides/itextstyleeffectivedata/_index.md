---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text style properties.
type: docs
url: /nl/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Onveranderlijk object dat effectieve tekstopmaak-eigenschappen bevat.

--------------------

Deze interface wordt samen met de [ITextStyle](../../com.aspose.slides/itextstyle) interface gebruikt om effectieve opmaakwaarden met overerving toegepast terug te geven.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Retourneert het niveau van de effectieve stijl. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Retourneert effectieve standaardparagraaf-eigenschappen. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


Retourneert het niveau van de effectieve stijl.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Nul-gebaseerde index van het niveau. Moet liggen in het interval 0..8. |

**Retourwaarde:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Effectieve opmaak van niveau [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


Retourneert effectieve standaardparagraaf-eigenschappen. Alleen-lezen [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Retourwaarde:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)
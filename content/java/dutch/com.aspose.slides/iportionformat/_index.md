---
title: IPortionFormat
second_title: Aspose.Slides voor Java API-referentie
description: Deze klasse bevat de opmaak-eigenschappen van het tekstgedeelte.
type: docs
url: /nl/com.aspose.slides/iportionformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Deze klasse bevat de opmaak-eigenschappen van het tekstgedeelte. In tegenstelling tot [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

--------------------

Deze klasse wordt gebruikt om de opmaak-eigenschappen van een tekstgedeelte die voor het specifieke gedeelte zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat u in de meeste gevallen waarden krijgt die “ongedefinieerd” betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde, te verkrijgen, moet u de [getEffective](../../com.aspose.slides/iportionformat\#getEffective)-methode gebruiken die een [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-instantie retourneert.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Geeft of stelt de bookmark-identifier terug. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Geeft of stelt de bookmark-identifier terug. |
| [getSmartTagClean()](#getSmartTagClean--) | Bepaalt of de smart tag moet worden opgeschoond. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Bepaalt of de smart tag moet worden opgeschoond. |
| [getEffective()](#getEffective--) | Haalt de effectieve opmaakgegevens van het gedeelte op met de overerving toegepast. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Geeft of stelt de bookmark-identifier terug. Lezen/schrijven String.

**Retour:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Geeft of stelt de bookmark-identifier terug. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Bepaalt of de smart tag moet worden opgeschoond. Geen overerving toegepast. Lezen/schrijven boolean.

**Retour:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Bepaalt of de smart tag moet worden opgeschoond. Geen overerving toegepast. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Haalt de effectieve opmaakgegevens van het gedeelte op met de overerving toegepast.

**Retour:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
---
title: IPortionFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Deze klasse bevat de tekstgedeelte-opmaak eigenschappen.
type: docs
url: /nl/com.aspose.slides/iportionformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Deze klasse bevat de tekstgedeelte-opmaak eigenschappen. In tegenstelling tot [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) zijn alle eigenschappen van deze klasse schrijfbaar.

--------------------

Deze klasse wordt gebruikt om de tekstgedeelte-opmaak eigenschappen die voor het specifieke gedeelte zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, zodat u in de meeste gevallen waarden ontvangt die “onbepaald” betekenen.

Om de effectieve opmaakparameterwaarden, inclusief geërfde, te verkrijgen, moet u de [getEffective](../../com.aspose.slides/iportionformat\#getEffective)-methode gebruiken die een [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-instantie retourneert.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Retourneert of stelt de bladwijzer-identifier in. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Retourneert of stelt de bladwijzer-identifier in. |
| [getSmartTagClean()](#getSmartTagClean--) | Bepaalt of de smart tag moet worden opgeschoond. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Bepaalt of de smart tag moet worden opgeschoond. |
| [getEffective()](#getEffective--) | Haalt de effectieve gedeelte-opmaakgegevens op met toepassing van de overerving. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Retourneert of stelt de bladwijzer-identifier in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Retourneert of stelt de bladwijzer-identifier in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Bepaalt of de smart tag moet worden opgeschoond. Geen overerving toegepast. Lezen/Schrijven boolean.

**Retour:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Bepaalt of de smart tag moet worden opgeschoond. Geen overerving toegepast. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Haalt de effectieve gedeelte-opmaakgegevens op met toepassing van de overerving.

**Retour:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - Een [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
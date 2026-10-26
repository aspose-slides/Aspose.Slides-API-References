---
title: IPortionFormat
second_title: Aspose.Slides pro Java API Reference
description: Tato třída obsahuje vlastnosti formátování textové části.
type: docs
url: /cs/com.aspose.slides/iportionformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

--------------------

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [getEffective](../../com.aspose.slides/iportionformat\#getEffective) method which returns a [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) instance.

## Metody

| Metoda | Popis |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returns or sets bookmark identifier. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Returns or sets bookmark identifier. |
| [getSmartTagClean()](#getSmartTagClean--) | Determines whether the smart tag should be cleaned. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determines whether the smart tag should be cleaned. |
| [getEffective()](#getEffective--) | Gets effective portion formatting data with the inheritance applied. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Vrací nebo nastavuje identifikátor záložky. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Vrací nebo nastavuje identifikátor záložky. Čtení/Zápis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Určuje, zda má být chytrá značka vyčištěna. Žádná dědičnost se nepoužívá. Čtení/Zápis boolean.

**Vrací:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Určuje, zda má být chytrá značka vyčištěna. Žádná dědičnost se nepoužívá. Čtení/Zápis boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Získá data formátování části s aplikovaným děděním.

**Vrací:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - Jedná se o [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
---
title: IPortionFormat
second_title: Aspose.Slides for Java API Referencia
description: Ez az osztály a szövegrész formázási tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/iportionformat/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Ez az osztály a szövegrész formázási tulajdonságait tartalmazza. A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-től eltérően az osztály összes tulajdonsága írható.

--------------------

Ez az osztály a konkrét részhez definiált szövegrész formázási tulajdonságok visszaadására és manipulálására szolgál. Ez azt jelenti, hogy az értékek lekérdezésekor nincs alkalmazva az öröklődés, így a legtöbb esetben „undefined” (nem definiált) értékeket kap.

Az öröklött formázási paraméterértékek hatékony lekéréséhez használni kell a [getEffective](../../com.aspose.slides/iportionformat\#getEffective) metódust, amely egy [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) példányt ad vissza.
## Módszerek

| Módszer | Leírás |
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


Visszaadja vagy beállítja a könyvjelző azonosítót. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```


Visszaadja vagy beállítja a könyvjelző azonosítót. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Megállapítja, hogy a smart tag-et tisztítani kell-e. Nincs alkalmazva öröklődés. Olvasás/írás boolean.

**Visszatér:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```


Megállapítja, hogy a smart tag-et tisztítani kell-e. Nincs alkalmazva öröklődés. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```


Az öröklődéssel alkalmazott hatékony formázási adatokat adja vissza.

**Visszatér:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
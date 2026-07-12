---
title: IPortionFormat
second_title: Aspose.Slides Androidra a Java API referencián keresztül
description: Ez az osztály tartalmazza a szövegrész formázási tulajdonságait.
type: docs
url: /hu/com.aspose.slides/iportionformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Ez az osztály tartalmazza a szövegrész formázási tulajdonságait. A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-tól eltérően az osztály összes tulajdonsága írható.

--------------------

Ez az osztály a visszaadáshoz és a szövegrész formázási tulajdonságainak manipulálásához használható, amelyeket az adott részhez definiáltak. Ez azt jelenti, hogy értékek lekérdezésekor nincs öröklődés alkalmazva, ezért a legtöbb esetben az értékek „undefined” jelentésűek.

Az örökölt értékeket is tartalmazó hatékony formázási paraméterértékek lekérdezéséhez használni kell a [getEffective](../../com.aspose.slides/iportionformat\#getEffective) metódust, amely egy [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) példányt ad vissza.
## Módszerek

| Metódus | Leírás |
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

Megállapítja, hogy a okos címkét meg kell-e tisztítani. Nincs öröklődés alkalmazva. Olvasás/írás boolean.

**Visszatér:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Megállapítja, hogy a okos címkét meg kell-e tisztítani. Nincs öröklődés alkalmazva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Megkapja a rész formázási adatát az öröklődés alkalmazásával.

**Visszatér:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides for Android Java API referencia
description: Megváltoztathatatlan objektum, amely a tényleges szövegrész formázási tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/iportionformateffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Megváltoztathatatlan objektum, amely a tényleges szövegrész formázási tulajdonságait tartalmazza.

--------------------

Ez az interfész a [IPortionFormat](../../com.aspose.slides/iportionformat) interfésszel együtt használható, hogy visszaadja a tényleges formázási értékeket öröklődéssel alkalmazva.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Visszaadja a könyvjelző azonosítót. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Visszaadja az egérkattintásra definiált hiperhivatkozást. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Visszaadja az egér fölé mozgatásra definiált hiperhivatkozást. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Visszaadja a könyvjelző azonosítót. Csak olvasható String.

**Visszatér:**
java.lang.String

### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


Visszaadja az egérkattintásra definiált hiperhivatkozást. Csak olvasható [IHyperlink](../../com.aspose.slides/ihyperlink).

**Visszatér:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


Visszaadja az egér fölé mozgatásra definiált hiperhivatkozást. Csak olvasható [IHyperlink](../../com.aspose.slides/ihyperlink).

**Visszatér:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides Java API referencia
description: A menedzser, amely az összes diatípushoz tartozó lábléc, dátum-idő és oldalszám helyőrzők viselkedését biztosítja.
type: docs
url: /hu/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

A menedzser, amely az összes diatípushoz tartozó lábléc, dátum-idő és oldalszám helyőrzők viselkedését biztosítja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Gets value indicating that a footer placeholder is present. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Gets value indicating that a page number placeholder is present. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Gets value indicating that a date-time placeholder is present. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Changes slide footer placeholder visibility. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Changes slide page number placeholder visibility. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Changes slide date-time placeholder visibility. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Sets text to slide footer placeholder. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Sets text to slide date-time placeholder. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


Visszaadja azt az értéket, amely jelzi, hogy a lábléc helyőrző jelen van. Olvasás: boolean.

**Visszatérési érték:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


Visszaadja azt az értéket, amely jelzi, hogy az oldal szám helyőrző jelen van. Olvasás: boolean.

**Visszatérési érték:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


Visszaadja azt az értéket, amely jelzi, hogy a dátum-idő helyőrző jelen van. Olvasás: boolean.

**Visszatérési érték:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


Módosítja a dia lábléc helyőrző láthatóságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – lábléc helyőrzőt láthatóvá teszi, egyébként – elrejti. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


Módosítja a dia oldal szám helyőrző láthatóságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – oldal szám helyőrzőt láthatóvá teszi, egyébként – elrejti. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


Módosítja a dia dátum-idő helyőrző láthatóságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – dátum-idő helyőrzőt láthatóvá teszi, egyébként – elrejti. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


Beállítja a szöveget a dia lábléc helyőrzőhöz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


Beállítja a szöveget a dia dátum-idő helyőrzőhöz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |
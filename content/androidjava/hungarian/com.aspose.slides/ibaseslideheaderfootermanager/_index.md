---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides for Android Java API hivatkozás
description: Egy menedzsert képvisel, amely a lábléc, dátum-idő és oldalszám helyfoglalók viselkedését kezeli minden diatípushoz.
type: docs
url: /hu/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Egy menedzsert képvisel, amely a lábléc, dátum-idő és oldalszám helyfoglalók viselkedését kezeli minden diatípushoz.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Visszaad egy értéket, amely jelzi, hogy a lábléc helyfoglaló jelen van. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Visszaad egy értéket, amely jelzi, hogy az oldalszám helyfoglaló jelen van. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Visszaad egy értéket, amely jelzi, hogy a dátum-idő helyfoglaló jelen van. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Megváltoztatja a dia lábléc helyfoglaló láthatóságát. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Megváltoztatja a dia oldalszám helyfoglaló láthatóságát. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Megváltoztatja a dia dátum-idő helyfoglaló láthatóságát. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Beállítja a szöveget a dia lábléc helyfoglalóhoz. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Beállítja a szöveget a dia dátum-idő helyfoglalóhoz. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```


Visszaad egy értéket, amely jelzi, hogy a lábléc helyfoglaló jelen van. Olvasás: boolean.

**Visszatér:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```


Visszaad egy értéket, amely jelzi, hogy az oldalszám helyfoglaló jelen van. Olvasás: boolean.

**Visszatér:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```


Visszaad egy értéket, amely jelzi, hogy a dátum-idő helyfoglaló jelen van. Olvasás: boolean.

**Visszatér:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```


Megváltoztatja a dia lábléc helyfoglaló láthatóságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – lábléc helyfoglalót láthatóvá teszi, egyébként elrejti. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```


Megváltoztatja a dia oldalszám helyfoglaló láthatóságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – oldalszám helyfoglalót láthatóvá teszi, egyébként elrejti. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```


Megváltoztatja a dia dátum-idő helyfoglaló láthatóságát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| isVisible | boolean | true – dátum-idő helyfoglalót láthatóvá teszi, egyébként elrejti. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```


Beállítja a szöveget a dia lábléc helyfoglalóhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```


Beállítja a szöveget a dia dátum-idő helyfoglalóhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Beállítandó szöveg. |
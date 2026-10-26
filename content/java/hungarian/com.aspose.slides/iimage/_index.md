---
title: IImage
second_title: Aspose.Slides Java API referencia
description: Egy raszteres vagy vektoros képet képvisel.
type: docs
url: /hu/com.aspose.slides/iimage/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Egy raszteres vagy vektoros képet képvisel.

--------------------

Ez az interfész közös absztrakciót biztosít a raszteres és vektoros képek kezeléséhez. A megvalósítások eltérhetnek az alapul szolgáló képtípustól függően.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Ment egy képet egy fájlba. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Ment egy képet egy fájlba a megadott formátumban. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Ment egy képet egy adatfolyamba a megadott formátumban. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Ment egy képet egy fájlba a megadott formátumban és minőségben. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Ment egy képet egy adatfolyamba a megadott formátumban és minőségben. |
| [getSize()](#getSize--) | Lekérdezi a kép méretét. |
| [getWidth()](#getWidth--) | Lekérdezi a kép szélességét pixelben. |
| [getHeight()](#getHeight--) | Lekérdezi a kép magasságát pixelben. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Ment egy képet egy fájlba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | java.lang.String | Az a fájl útvonala, ahová a kép mentésre kerül. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Ment egy képet egy fájlba a megadott formátumban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | java.lang.String | Az a fájl útvonala, ahová a kép mentésre kerül. |
| format | int | A kép formátuma. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Ment egy képet egy adatfolyamba a megadott formátumban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Az adatfolyam, ahová a kép mentésre kerül. |
| format | int | A kép formátuma. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Ment egy képet egy fájlba a megadott formátumban és minőségben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | java.lang.String | Az a fájl útvonala, ahová a kép mentésre kerül. |
| format | int | A kép formátuma. |
| quality | int | A mentett kép minősége (0-tól 100-ig). Ez a paraméter csak a [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) mentésére hat, minden más formátúnál figyelmen kívül van hagyva. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Ment egy képet egy adatfolyamba a megadott formátumban és minőségben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Az adatfolyam, ahová a kép mentésre kerül. |
| format | int | A kép formátuma. |
| quality | int | A mentett kép minősége (0-tól 100-ig). Ez a paraméter csak a [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) mentésére hat, minden más formátúnál figyelmen kívül van hagyva. |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

Lekérdezi a kép méretét.

**Visszatérési érték:**
java.awt.Dimension
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Lekérdezi a kép szélességét pixelben.

**Visszatérési érték:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Lekérdezi a kép magasságát pixelben.

**Visszatérési érték:**
int
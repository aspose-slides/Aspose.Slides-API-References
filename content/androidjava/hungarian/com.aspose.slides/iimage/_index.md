---
title: IImage
second_title: Aspose.Slides Androidhoz a Java API hivatkozással
description: Raster- vagy vektorképet képvisel.
type: docs
url: /hu/com.aspose.slides/iimage/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Raster- vagy vektorképet képvisel.

--------------------

Ez az interfész közös absztrakciót biztosít a raster- és vektorképek kezeléséhez. A megvalósítások az alapul szolgáló képtípustól függően változhatnak.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Elmenti a képet egy fájlba. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Elmenti a képet egy fájlba a megadott formátumban. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Elmenti a képet egy adatfolyamba a megadott formátumban. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Elmenti a képet egy fájlba a megadott formátumban és minőségben. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Elmenti a képet egy adatfolyamba a megadott formátumban és minőségben. |
| [getSize()](#getSize--) | A kép méretét adja vissza. |
| [getWidth()](#getWidth--) | A kép szélességét adja vissza pixelekben. |
| [getHeight()](#getHeight--) | A kép magasságát adja vissza pixelekben. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Elmenti a képet egy fájlba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | java.lang.String | Az az elérési út, ahová a kép el lesz mentve. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Elmenti a képet egy fájlba a megadott formátumban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | java.lang.String | Az az elérési út, ahová a kép el lesz mentve. |
| format | int | A kép formátuma. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Elmenti a képet egy adatfolyamba a megadott formátumban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Az az adatfolyam, ahová a kép el lesz mentve. |
| format | int | A kép formátuma. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Elmenti a képet egy fájlba a megadott formátumban és minőségben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | java.lang.String | Az az elérési út, ahová a kép el lesz mentve. |
| format | int | A kép formátuma. |
| quality | int | A mentett kép minősége (0-tól 100-ig). Ez a paraméter csak a [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) mentésére vonatkozik; minden más formátúrnál figyelmen kívül van hagyva. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Elmenti a képet egy adatfolyamba a megadott formátumban és minőségben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Az az adatfolyam, ahová a kép el lesz mentve. |
| format | int | A kép formátuma. |
| quality | int | A mentett kép minősége (0-tól 100-ig). Ez a paraméter csak a [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) mentésére vonatkozik; minden más formátúrnál figyelmen kívül van hagyva. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

A kép méretét adja vissza.

**Visszatérési érték:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

A kép szélességét adja vissza pixelekben.

**Visszatérési érték:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

A kép magasságát adja vissza pixelekben.

**Visszatérési érték:**
int
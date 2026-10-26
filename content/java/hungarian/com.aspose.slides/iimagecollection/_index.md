---
title: IImageCollection
second_title: Aspose.Slides Java API referencia
description: PPImage gyűjteményt képviseli.
type: docs
url: /hu/com.aspose.slides/iimagecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

PPImage gyűjteményt képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a képet az indexe alapján. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Képet ad a prezentációhoz. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Képet ad a prezentációhoz egy adatfolyamból. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Létrehozza és hozzáadja a képet a prezentációhoz egy adatfolyamból. |
| [addImage(byte[] buffer)](#addImage-byte---) | Képet ad a prezentációhoz a megadott pufferből. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Másik prezentációból egy képmásolatot ad hozzá. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Képet ad a prezentációhoz egy SVG objektumból. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Visszaadja a képet az indexe alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Index. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Kép.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Képet ad a prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | A hozzáadandó kép.

--------------------

Ez a módszer WMF/EMF metafájlokat raszteres PNG képpé konvertál, mielőtt beillesztené a prezentációba. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Képet ad a prezentációhoz egy adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Az adatfolyam, amelyből a képet hozzáadja.

--------------------

Ez a módszer WMF/EMF metafájlokat a prezentációhoz adhat hozzá anélkül, hogy raszteres PNG képpé konvertálná őket. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Létrehozza és hozzáadja a képet a prezentációhoz egy adatfolyamból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Az adatfolyam, amelyből a képfájlt hozzáadja. |
| loadingStreamBehavior | int | Az a viselkedés, amely az adatfolyamra lesz alkalmazva. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Képet ad a prezentációhoz a megadott pufferből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | byte[] | Puffer. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Másik prezentációból egy képmásolatot ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Forráskép. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Képet ad a prezentációhoz egy SVG objektumból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG kép objektum [ISvgImage](../../com.aspose.slides/isvgimage) |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Hozzáadott kép.
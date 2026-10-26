---
title: IImageCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: PPImage gyűjteményt reprezentál.
type: docs
url: /hu/com.aspose.slides/iimagecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Represents collection of PPImage.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a képet az index alapján. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Képet ad egy prezentációhoz. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Képet ad egy prezentációhoz egy folyamatról. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Képet hoz létre és ad egy prezentációhoz egy folyamatról. |
| [addImage(byte[] buffer)](#addImage-byte---) | Képet ad egy prezentációhoz a megadott pufferból. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Képmásolatot ad egy másik prezentációból. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Képet ad egy prezentációhoz SVG objektumból. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Visszaadja a képet az index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Képet ad egy prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Hozzáadandó kép. |

--------------------

Ez a metódus WMF/EMF meta fájlokat raszteres PNG képpé konvertál, mielőtt a prezentációba beillesztené. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Képet ad egy prezentációhoz egy folyamatról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Folyam, amiből a képet felveszi. |

--------------------

Ez a metódus WMF/EMF meta fájlokat ad a prezentációhoz anélkül, hogy raszteres PNG képpé konvertálná őket. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Képet hoz létre és ad egy prezentációhoz egy folyamatról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Folyam, amiből a képfájlt felveszi. |
| loadingStreamBehavior | int | A viselkedés, amely a folyamra alkalmazandó. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Added [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Képet ad egy prezentációhoz a megadott pufferból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | byte[] | Puffer. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Képmásolatot ad egy másik prezentációból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Forráskép. |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Képet ad egy prezentációhoz SVG objektumból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG kép objektum [ISvgImage](../../com.aspose.slides/isvgimage) |

**Visszatér:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
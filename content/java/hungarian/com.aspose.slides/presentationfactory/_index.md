---
title: PresentationFactory
second_title: Aspose.Slides for Java API referencia
description: Lehetővé teszi a prezentáció létrehozását COM interfészen keresztül
type: docs
url: /hu/com.aspose.slides/presentationfactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Lehetővé teszi prezentáció létrehozását COM interfészen keresztül

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getInstance()](#getInstance--) | Presentation factory static instance. |
| [createPresentation()](#createPresentation--) | Creates new presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Creates new presentation with additional load options |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Creates new PresentationInfo object from file and binds presentation to it. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Creates new PresentationInfo object from stream and binds presentation to it. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Reads an existing presentation from array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Reads an existing presentation from array with additional load options |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Reads an existing presentation from stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Reads an existing presentation from file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Retrieves the raw text from the slides |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


Presentation factory static instance. Read-only [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Visszatérési érték:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


Új prezentációt hoz létre.

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation) - Új prezentáció
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```


Új prezentációt hoz létre további betöltési beállításokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation) - Új prezentáció
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


Új PresentationInfo objektumot hoz létre fájlból, és a prezentációt hozzá köti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Prezentációs fájl. |

**Visszatérési érték:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - A prezentációhoz kapcsolt információ.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


Új PresentationInfo objektumot hoz létre streame-ből, és a prezentációt hozzá köti. Információt kap a megadott streamben lévő prezentációról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Prezentációs stream. |

**Visszatérési érték:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - A prezentációhoz kapcsolt információ.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```


Meglévő prezentációt olvas be tömbből

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Beolvasandó tömb |

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Meglévő prezentációt olvas be tömbből további betöltési beállításokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Beolvasandó tömb |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```


Meglévő prezentációt olvas be streamből

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Beolvasandó bemeneti stream |

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Meglévő prezentációt olvas be streamből további betöltési beállításokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Beolvasandó bemeneti stream |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```


Meglévő prezentációt olvas be fájlból

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Fájlnév |

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```


Meglévő prezentációt olvas be fájlból további betöltési beállításokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Fájlnév |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


A diak nyers szövegét adja vissza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Bemeneti fájl |
| mode | int | Kivonási mód |

**Visszatérési érték:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, a nyers diák szövegét reprezentálva
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


A diak nyers szövegét adja vissza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti stream |
| mode | int | Kivonási mód |

**Visszatérési érték:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, a nyers diák szövegét reprezentálva
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


A diak nyers szövegét adja vissza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti stream |
| mode | int | Kivonási mód |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatérési érték:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, a nyers diák szövegét reprezentálva
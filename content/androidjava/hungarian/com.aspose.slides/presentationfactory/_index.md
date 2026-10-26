---
title: PresentationFactory
second_title: Aspose.Slides for Android a Java API hivatkozás alapján
description: Lehetővé teszi a prezentáció létrehozását COM interfészen keresztül
type: docs
url: /hu/com.aspose.slides/presentationfactory/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Lehetővé teszi a prezentáció létrehozását COM interfészen keresztül

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
| [getInstance()](#getInstance--) | Prezentációgyári statikus példány. |
| [createPresentation()](#createPresentation--) | Új prezentációt hoz létre. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Új prezentációt hoz létre további betöltési beállításokkal |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Új PresentationInfo objektumot hoz létre a fájlból, és a prezentációt hozzá kapcsolja. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Új PresentationInfo objektumot hoz létre az adatfolyamból, és a prezentációt hozzá kapcsolja. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Meglévő prezentációt olvas be tömbből |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Meglévő prezentációt olvas be tömbből további betöltési beállításokkal |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Meglévő prezentációt olvas be adatfolyamból |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Meglévő prezentációt olvas be adatfolyamból további betöltési beállításokkal |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Meglévő prezentációt olvas be fájlból |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Meglévő prezentációt olvas be adatfolyamból további betöltési beállításokkal |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | A diák nyers szövegét adja vissza |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | A diák nyers szövegét adja vissza |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | A diák nyers szövegét adja vissza |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Prezentációgyári statikus példány. Csak olvasható [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Visszatér:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

Új prezentációt hoz létre.

**Visszatér:**
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

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation) - Új prezentáció
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

Új PresentationInfo objektumot hoz létre a fájlból, és a prezentációt hozzá kapcsolja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Prezentációfájl. |

**Visszatér:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Prezentációhoz kapcsolt információ.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

Új PresentationInfo objektumot hoz létre az adatfolyamból, és a prezentációt hozzá kapcsolja. Információt kap a megadott áramlatban lévő prezentációról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Prezentáció adatfolyam. |

**Visszatér:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Prezentációhoz kapcsolt információ.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

Meglévő prezentációt olvas be tömbből

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Olvasandó tömb |

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Meglévő prezentációt olvas be tömbből további betöltési beállításokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Olvasandó tömb |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPPresentation readPresentation(InputStream stream)
```

Meglévő prezentációt olvas be adatfolyamból

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Olvasandó bemeneti adatfolyam |

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Meglévő prezentációt olvas be adatfolyamból további betöltési beállításokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Olvasandó bemeneti adatfolyam |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatér:**
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

**Visszatér:**
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

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

A diák nyers szövegét adja vissza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Bemeneti fájl |
| mode | int | Kivonási mód |

**Visszatér:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, és a nyers diák szövegét képviseli
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

A diák nyers szövegét adja vissza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti adatfolyam |
| mode | int | Kivonási mód |

**Visszatér:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, és a nyers diák szövegét képviseli
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

A diák nyers szövegét adja vissza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti adatfolyam |
| mode | int | Kivonási mód |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatér:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, és a nyers diák szövegét képviseli
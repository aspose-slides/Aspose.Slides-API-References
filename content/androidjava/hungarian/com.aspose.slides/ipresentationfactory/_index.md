---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi prezentáció létrehozását a COM interfészen keresztül
type: docs
url: /hu/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Lehetővé teszi prezentáció létrehozását a COM interfészen keresztül
## Módszerek

| Method | Description |
| --- | --- |
| [createPresentation()](#createPresentation--) | Új prezentációt hoz létre. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Új prezentációt hoz létre további betöltési beállításokkal. |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Információt kér le a megadott fájlban lévő prezentációról. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Információt kér le a megadott adatfolyamban lévő prezentációról. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Meglévő prezentációt olvas be tömbből |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Meglévő prezentációt olvas be tömbből további betöltési beállításokkal |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Meglévő prezentációt olvas be adatfolyamból |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Meglévő prezentációt olvas be adatfolyamból további betöltési beállításokkal |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Meglévő prezentációt olvas be fájlból |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Meglévő prezentációt olvas be adatfolyamból további betöltési beállításokkal |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Lekéri a diák nyers szövegét |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Lekéri a diák nyers szövegét |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Lekéri a diák nyers szövegét |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Új prezentációt hoz létre.

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Új prezentáció
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

Új prezentációt hoz létre további betöltési beállításokkal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Új prezentáció
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

Információt kér le a megadott fájlban lévő prezentációról.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Prezentáció fájlja. |

**Returns:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Prezentáció információ
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Információt kér le a megadott adatfolyamban lévő prezentációról.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Prezentáció adatfolyama. |

**Returns:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Prezentáció információ.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

Meglévő prezentációt olvas be tömbből

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | A beolvasandó tömb |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Meglévő prezentációt olvas be tömbből további betöltési beállításokkal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | A beolvasandó tömb |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Meglévő prezentációt olvas be adatfolyamból

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A beolvasandó bemeneti adatfolyam |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Meglévő prezentációt olvas be adatfolyamból további betöltési beállításokkal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A beolvasandó bemeneti adatfolyam |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Meglévő prezentációt olvas be fájlból

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fájl neve |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Meglévő prezentációt olvas be fájlból további betöltési beállításokkal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fájl neve |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

Lekéri a diák nyers szövegét

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Bemeneti fájl |
| mode | int | Kivonási mód |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, amely a diák nyers szövegét reprezentálja
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

Lekéri a diák nyers szövegét

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti adatfolyam |
| mode | int | Kivonási mód |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, amely a diák nyers szövegét reprezentálja
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Lekéri a diák nyers szövegét

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti adatfolyam |
| mode | int | Kivonási mód |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Returns:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, amely a diák nyers szövegét reprezentálja
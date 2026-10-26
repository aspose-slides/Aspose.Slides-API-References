---
title: IPresentationFactory
second_title: Aspose.Slides for Java API Referencia
description: Lehetővé teszi a prezentáció létrehozását COM interfészen keresztül
type: docs
url: /hu/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Lehetővé teszi a prezentáció létrehozását COM interfészen keresztül
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createPresentation()](#createPresentation--) | Új prezentációt hoz létre. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Új prezentációt hoz létre további betöltési beállításokkal. |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Információt kér le a megadott fájlban lévő prezentációról. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Információt kér le a megadott folyam által tartalmazott prezentációról. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Olvas egy meglévő prezentációt tömbből. |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Olvas egy meglévő prezentációt tömbből további betöltési beállításokkal. |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Olvas egy meglévő prezentációt folyamról. |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Olvas egy meglévő prezentációt folyamról további betöltési beállításokkal. |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Olvas egy meglévő prezentációt fájlból. |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Olvas egy meglévő prezentációt folyamról további betöltési beállításokkal. |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | A diák nyers szövegét adja vissza. |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | A diák nyers szövegét adja vissza. |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | A diák nyers szövegét adja vissza. |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Új prezentációt hoz létre.

**Visszatér:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Új prezentáció
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
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
public abstract IPresentationInfo getPresentationInfo(String file)
```

Információt kér le a megadott fájlban lévő prezentációról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Prezentáció fájlja. |

**Visszatér:**  
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Prezentációinformáció
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Információt kér le a megadott folyam által tartalmazott prezentációról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Prezentáció folyam. |

**Visszatér:**  
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Prezentációinformáció.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

Olvas egy meglévő prezentációt tömbből

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Olvasandó tömb |

**Visszatér:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Olvas egy meglévő prezentációt tömbből további betöltési beállításokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Olvasandó tömb |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatér:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Olvas egy meglévő prezentációt folyamról

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Olvasandó bemeneti folyam |

**Visszatér:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Olvas egy meglévő prezentációt folyamról további betöltési beállításokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Olvasandó bemeneti folyam |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatér:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Olvas egy meglévő prezentációt fájlból

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Fájlnév |

**Visszatér:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Olvas egy meglévő prezentációt fájlból további betöltési beállításokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Fájlnév |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatér:**  
[IPresentation](../../com.aspose.slides/ipresentation) - Beolvasott prezentáció
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

A diák nyers szövegét adja vissza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Bemeneti fájl |
| mode | int | Kinyerési mód |

**Visszatér:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, amely a diák nyers szövegét képviseli
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

A diák nyers szövegét adja vissza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti folyam |
| mode | int | Kinyerési mód |

**Visszatér:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, amely a diák nyers szövegét képviseli
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

A diák nyers szövegét adja vissza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti folyam |
| mode | int | Kinyerési mód |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Betöltési beállítások |

**Visszatér:**  
[IPresentationText](../../com.aspose.slides/ipresentationtext) - A PresentationText példány, amely a SlideText tömböt tartalmazza, amely a diák nyers szövegét képviseli
---
title: IImageCollection
second_title: Aspose.Slides pro Android pomocí Java API
description: Representuje kolekci PPImage.
type: docs
url: /cs/com.aspose.slides/iimagecollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Represents collection of PPImage.

## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací obrázek podle jeho indexu. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Přidá obrázek do prezentace. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Přidá obrázek do prezentace ze streamu. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Vytvoří a přidá obrázek do prezentace ze streamu. |
| [addImage(byte[] buffer)](#addImage-byte---) | Přidá obrázek do prezentace ze specifikovaného bufferu. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Přidá kopii obrázku z jiné prezentace. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Přidá obrázek do prezentace z objektu SVG. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

Vrací obrázek podle jeho indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

Přidá obrázek do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Obrázek k přidání. |

--------------------

Tato metoda převádí soubory WMF/EMF na rastrový PNG obrázek před vložením do prezentace. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

Přidá obrázek do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se má obrázek přidat. |

--------------------

Tato metoda může přidat soubory WMF/EMF do prezentace bez jejich převodu na rastrový PNG obrázek. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Vytvoří a přidá obrázek do prezentace ze streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, ze kterého se má obrázek přidat. |
| loadingStreamBehavior | int | Chování, které bude použito na stream. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidáno [IPPImage](../../com.aspose.slides/ippimage).

### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

Přidá obrázek do prezentace ze specifikovaného bufferu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

Přidá kopii obrázku z jiné prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Zdrojový obrázek. |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

Přidá obrázek do prezentace z objektu SVG.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Objekt SVG obrázku [ISvgImage](../../com.aspose.slides/isvgimage) |

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage) - Přidaný obrázek.
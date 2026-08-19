---
title: PresentationFactory
second_title: Aspose.Slides pro Java – Referenční příručka API
description: Umožňuje vytvořit prezentaci přes COM rozhraní
type: docs
url: /cs/com.aspose.slides/presentationfactory/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Umožňuje vytvořit prezentaci přes COM rozhraní

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
## Konstruktory

| Constructor | Description |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Metody

| Method | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Statická instance továrny na prezentace. |
| [createPresentation()](#createPresentation--) | Vytvoří novou prezentaci. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Vytvoří novou prezentaci s dodatečnými možnostmi načítání |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Vytvoří nový objekt PresentationInfo ze souboru a sváže prezentaci s ním. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Vytvoří nový objekt PresentationInfo ze streamu a sváže prezentaci s ním. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Načte existující prezentaci z pole |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Načte existující prezentaci z pole s dodatečnými možnostmi načítání |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Načte existující prezentaci ze streamu |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Načte existující prezentaci ze streamu s dodatečnými možnostmi načítání |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Načte existující prezentaci ze souboru |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Načte existující prezentaci ze streamu s dodatečnými možnostmi načítání |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Získá surový text ze snímků |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Získá surový text ze snímků |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Získá surový text ze snímků |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Statická instance továrny na prezentace. Pouze ke čtení [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Návratová hodnota:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

Vytvoří novou prezentaci.

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nová prezentace
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

Vytvoří novou prezentaci s dodatečnými možnostmi načítání

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načítání |

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nová prezentace
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

Vytvoří nový objekt PresentationInfo ze souboru a sváže prezentaci s ním.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Soubor prezentace. |

**Návratová hodnota:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informace o prezentaci svázané s prezentací.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

Vytvoří nový objekt PresentationInfo ze streamu a sváže prezentaci s ním. Získá informace o prezentaci ve specifikovaném streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream prezentace. |

**Návratová hodnota:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informace o prezentaci svázané s prezentací.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

Načte existující prezentaci z pole

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Pole k načtení |

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Načte existující prezentaci z pole s dodatečnými možnostmi načítání

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Pole k načtení |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načítání |

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

Načte existující prezentaci ze streamu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní stream k načtení |

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Načte existující prezentaci ze streamu s dodatečnými možnostmi načítání

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní stream k načtení |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načítání |

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

Načte existující prezentaci ze souboru

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Název souboru |

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```

Načte existující prezentaci ze souboru s dodatečnými možnostmi načítání

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Název souboru |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načítání |

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation) - Načtená prezentace
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

Získá surový text ze snímků

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Vstupní soubor |
| mode | int | Extrahovací režim |

**Návratová hodnota:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instance třídy PresentationText obsahující pole SlideText představující surový text snímků
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

Získá surový text ze snímků

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní stream |
| mode | int | Extrahovací režim |

**Návratová hodnota:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instance třídy PresentationText obsahující pole SlideText představující surový text snímků
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Získá surový text ze snímků

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní stream |
| mode | int | Extrahovací režim |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načítání |

**Návratová hodnota:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instance třídy PresentationText obsahující pole SlideText představující surový text snímků
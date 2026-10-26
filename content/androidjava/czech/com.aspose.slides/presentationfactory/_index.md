---
title: PresentationFactory
second_title: Aspose.Slides pro Android přes Java API Reference
description: Umožňuje vytvářet prezentaci pomocí COM rozhraní
type: docs
url: /cs/com.aspose.slides/presentationfactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Umožňuje vytvářet prezentaci pomocí COM rozhraní

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

| Konstruktor | Popis |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Metody

| Metoda | Popis |
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


Statická instance tovární prezentace. Pouze pro čtení [PresentationFactory](../../com.aspose.slides/presentationfactory).

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


Vytvoří novou prezentaci s dodatečnými možnostmi načtení

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načtení |

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nová prezentace
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


Vytvoří nový objekt PresentationInfo ze souboru a propojí ho s prezentací.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Soubor prezentace. |

**Návratová hodnota:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informace o prezentaci navázaná na prezentaci.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


Vytvoří nový objekt PresentationInfo ze streamu a propojí ho s prezentací. Získá informace o prezentaci ve specifikovaném streamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream prezentace. |

**Návratová hodnota:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informace o prezentaci navázaná na prezentaci.
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


Načte existující prezentaci z pole s dodatečnými možnostmi načtení

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Pole k načtení |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načtení |

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


Načte existující prezentaci ze streamu s dodatečnými možnostmi načtení

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní stream k načtení |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načtení |

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
public final IPPresentation readPresentation(String file, ILoadOptions options)
```


Načte existující prezentaci ze souboru s dodatečnými možnostmi načtení

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Název souboru |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načtení |

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
| mode | int | Režim extrakce |

**Návratová hodnota:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instance PresentationText obsahující pole SlideText představující surový text snímků
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


Získá surový text ze snímků

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní stream |
| mode | int | Režim extrakce |

**Návratová hodnota:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instance PresentationText obsahující pole SlideText představující surový text snímků
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Získá surový text ze snímků

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní stream |
| mode | int | Režim extrakce |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Možnosti načtení |

**Návratová hodnota:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instance PresentationText obsahující pole SlideText představující surový text snímků
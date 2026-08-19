---
title: PresentationFactory
second_title: Aspose.Slides voor Java API-referentie
description: Staat toe om een presentatie te maken via de COM-interface
type: docs
url: /nl/com.aspose.slides/presentationfactory/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Staat toe om een presentatie te maken via de COM-interface

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getInstance()](#getInstance--) | Presentatie-fabriek statisch exemplaar. |
| [createPresentation()](#createPresentation--) | Maakt een nieuwe presentatie. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Maakt een nieuwe presentatie met aanvullende laadopties |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Maakt een nieuw PresentationInfo-object van een bestand en bindt de presentatie eraan. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Maakt een nieuw PresentationInfo-object van een stream en bindt de presentatie eraan. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Leest een bestaande presentatie uit een array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een array met aanvullende laadopties |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Leest een bestaande presentatie uit een stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een stream met aanvullende laadopties |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Leest een bestaande presentatie uit een bestand |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een stream met aanvullende laadopties |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Haalt de ruwe tekst van de dia's op |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Haalt de ruwe tekst van de dia's op |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Haalt de ruwe tekst van de dia's op |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


Presentatie-fabriek statisch exemplaar. Alleen-lezen [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Retour:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


Maakt een nieuwe presentatie.

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nieuwe presentatie
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```


Maakt een nieuwe presentatie met aanvullende laadopties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nieuwe presentatie
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


Maakt een nieuw PresentationInfo-object van een bestand en bindt de presentatie eraan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Presentatie-bestand. |

**Retour:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentatie-info gebonden aan de presentatie.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


Maakt een nieuw PresentationInfo-object van een stream en bindt de presentatie eraan. Haalt informatie op over de presentatie in de opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Presentatiestroom. |

**Retour:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentatie-info gebonden aan de presentatie.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPPresentation readPresentation(byte[] data)
```


Leest een bestaande presentatie uit een array

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Array om te lezen |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen presentatie
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Leest een bestaande presentatie uit een array met aanvullende laadopties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Array om te lezen |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen presentatie
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```


Leest een bestaande presentatie uit een stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstream om te lezen |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen presentatie
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Leest een bestaande presentatie uit een stream met aanvullende laadopties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstream om te lezen |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen presentatie
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPPresentation readPresentation(String file)
```


Leest een bestaande presentatie uit een bestand

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Bestandsnaam |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen presentatie
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```


Leest een bestaande presentatie uit een stream met aanvullende laadopties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Bestandsnaam |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen presentatie
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


Haalt de ruwe tekst van de dia's op

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Invoergegevensbestand |
| mode | int | Extractiemodus |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat met de ruwe tekst van de dia's
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


Haalt de ruwe tekst van de dia's op

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstream |
| mode | int | Extractiemodus |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat met de ruwe tekst van de dia's
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Haalt de ruwe tekst van de dia's op

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstream |
| mode | int | Extractiemodus |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat met de ruwe tekst van de dia's
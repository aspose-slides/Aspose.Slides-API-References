---
title: PresentationFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Hiermee kan een presentatie worden gemaakt via een COM-interface
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

Hiermee kan een presentatie worden gecreëerd via een COM-interface

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

## Constructoren

| Constructor | Description |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Methoden

| Method | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Statische instantie van de presentatiefabriek. |
| [createPresentation()](#createPresentation--) | Maakt een nieuwe presentatie. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Maakt een nieuwe presentatie met extra laadopties |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Maakt een nieuw PresentationInfo-object van een bestand en bindt de presentatie eraan. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Maakt een nieuw PresentationInfo-object van een stream en bindt de presentatie eraan. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Leest een bestaande presentatie uit een array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een array met extra laadopties |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Leest een bestaande presentatie uit een stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een stream met extra laadopties |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Leest een bestaande presentatie uit een bestand |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een stream met extra laadopties |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Haalt de ruwe tekst op van de dia's |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Haalt de ruwe tekst op van de dia's |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Haalt de ruwe tekst op van de dia's |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Statische instantie van de presentatiefabriek. Alleen-lezen [PresentationFactory](../../com.aspose.slides/presentationfactory).

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

Maakt een nieuwe presentatie met extra laadopties

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Presentatie-bestand. |

**Retour:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentatie-informatie gekoppeld aan de presentatie.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

Maakt een nieuw PresentationInfo-object van een stream en bindt de presentatie eraan. Haalt informatie op over de presentatie in de opgegeven stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Presentatiestream. |

**Retour:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentatie-informatie gekoppeld aan de presentatie.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

Leest een bestaande presentatie uit een array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Array om te lezen |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Leest een bestaande presentatie uit een array met extra laadopties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Array om te lezen |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

Leest een bestaande presentatie uit een stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom om te lezen |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Leest een bestaande presentatie uit een stream met extra laadopties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom om te lezen |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

Leest een bestaande presentatie uit een bestand

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Bestandsnaam |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```

Leest een bestaande presentatie uit een stream met extra laadopties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Bestandsnaam |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

Haalt de ruwe tekst op van de dia's

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Invoebestand |
| mode | int | Extractiemodus |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat en de ruwe dia-tekst representeert
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

Haalt de ruwe tekst op van de dia's

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom |
| mode | int | Extractiemodus |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat en de ruwe dia-tekst representeert
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Haalt de ruwe tekst op van de dia's

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom |
| mode | int | Extractiemodus |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat en de ruwe dia-tekst representeert
---
title: IPresentationFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe een presentatie te maken via COM-interface
type: docs
url: /nl/com.aspose.slides/ipresentationfactory/
---``` 
public interface IPresentationFactory
```

Staat toe een presentatie te maken via COM-interface
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createPresentation()](#createPresentation--) | Maakt een nieuwe presentatie. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Maakt een nieuwe presentatie met aanvullende laadopties |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Haalt info over presentatie op in opgegeven bestand. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Haalt info over presentatie op in opgegeven stream. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Leest een bestaande presentatie uit een array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een array met aanvullende laadopties |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Leest een bestaande presentatie uit een stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een stream met aanvullende laadopties |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Leest een bestaande presentatie uit een bestand |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een stream met aanvullende laadopties |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Haalt de onbewerkte tekst uit de dia's op |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Haalt de onbewerkte tekst uit de dia's op |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Haalt de onbewerkte tekst uit de dia's op |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```


Maakt een nieuwe presentatie.

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nieuwe presentatie
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
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
public abstract IPresentationInfo getPresentationInfo(String file)
```


Haalt info over presentatie op in opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Presentatiebestand. |

**Retour:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentatie-info
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```


Haalt info over presentatie op in opgegeven stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Presentatiestream. |

**Retour:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentatie-info.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```


Leest een bestaande presentatie uit een array

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Array om te lezen |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen van presentatie
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Leest een bestaande presentatie uit een array met aanvullende laadopties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Array om te lezen |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen van presentatie
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```


Leest een bestaande presentatie uit een stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom om te lezen |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen van presentatie
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Leest een bestaande presentatie uit een stream met aanvullende laadopties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom om te lezen |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen van presentatie
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```


Leest een bestaande presentatie uit een bestand

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Bestandsnaam |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen van presentatie
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```


Leest een bestaande presentatie uit een stream met aanvullende laadopties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Bestandsnaam |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Lezen van presentatie
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```


Haalt de onbewerkte tekst uit de dia's op

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Invoergebied |
| mode | int | Extractiemodus |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat die de onbewerkte tekst van de dia's weergeeft
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```


Haalt de onbewerkte tekst uit de dia's op

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom |
| mode | int | Extractiemodus |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat die de onbewerkte tekst van de dia's weergeeft
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Haalt de onbewerkte tekst uit de dia's op

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom |
| mode | int | Extractiemodus |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat die de onbewerkte tekst van de dia's weergeeft
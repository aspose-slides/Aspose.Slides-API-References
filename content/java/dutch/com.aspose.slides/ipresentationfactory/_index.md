---
title: IPresentationFactory
second_title: Aspose.Slides for Java API Reference
description: Staat toe om een presentatie te maken via COM-interface
type: docs
url: /nl/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Staat toe om een presentatie te maken via COM-interface
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createPresentation()](#createPresentation--) | Maakt een nieuwe presentatie. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Maakt een nieuwe presentatie met aanvullende laadopties |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Haalt informatie over een presentatie op in het opgegeven bestand. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Haalt informatie over een presentatie op in de opgegeven stroom. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Leest een bestaande presentatie uit een array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een array met aanvullende laadopties |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Leest een bestaande presentatie uit een stroom |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een stroom met aanvullende laadopties |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Leest een bestaande presentatie uit een bestand |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Leest een bestaande presentatie uit een stroom met aanvullende laadopties |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Haalt de ruwe tekst van de dia's op |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Haalt de ruwe tekst van de dia's op |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Haalt de ruwe tekst van de dia's op |
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

Haalt informatie over een presentatie op in het opgegeven bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Presentatiebestand. |

**Retour:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentatie-informatie
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Haalt informatie over een presentatie op in de opgegeven stroom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Presentatiestroom. |

**Retour:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentatie-informatie.
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
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
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
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Leest een bestaande presentatie uit een stroom

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom om te lezen |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Leest een bestaande presentatie uit een stroom met aanvullende laadopties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom om te lezen |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
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
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Leest een bestaande presentatie uit een stroom met aanvullende laadopties

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Bestandsnaam |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelezen presentatie
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

Haalt de ruwe tekst van de dia's op

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Invoerbestand |
| mode | int | Extractiemodus |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat die de ruwe dia-tekst weergeeft
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

Haalt de ruwe tekst van de dia's op

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom |
| mode | int | Extractiemodus |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat die de ruwe dia-tekst weergeeft
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Haalt de ruwe tekst van de dia's op

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom |
| mode | int | Extractiemodus |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laadopties |

**Retour:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - De instantie van PresentationText die de SlideText-array bevat die de ruwe dia-tekst weergeeft
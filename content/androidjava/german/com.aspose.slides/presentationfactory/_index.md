---
title: PresentationFactory
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Ermöglicht das Erstellen von Präsentationen über die COM-Schnittstelle
type: docs
url: /de/com.aspose.slides/presentationfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Ermöglicht das Erstellen von Präsentationen über die COM-Schnittstelle

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInstance()](#getInstance--) | Statische Instanz der Präsentationsfabrik. |
| [createPresentation()](#createPresentation--) | Erstellt eine neue Präsentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Erstellt eine neue Präsentation mit zusätzlichen Ladeoptionen |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Erstellt ein PresentationInfo-Objekt aus einer Datei und bindet die Präsentation daran. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Erstellt ein PresentationInfo-Objekt aus einem Stream und bindet die Präsentation daran. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Liest eine vorhandene Präsentation aus einem Array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Liest eine vorhandene Präsentation aus einem Array mit zusätzlichen Ladeoptionen |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Liest eine vorhandene Präsentation aus einem Stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Liest eine vorhandene Präsentation aus einem Stream mit zusätzlichen Ladeoptionen |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Liest eine vorhandene Präsentation aus einer Datei |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Liest eine vorhandene Präsentation aus einem Stream mit zusätzlichen Ladeoptionen |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Ruft den Rohtext aus den Folien ab |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Ruft den Rohtext aus den Folien ab |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Ruft den Rohtext aus den Folien ab |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


Statische Instanz der Präsentationsfabrik. Nur lesbar [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Rückgabe:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


Erstellt eine neue Präsentation.

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Neue Präsentation
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```


Erstellt eine neue Präsentation mit zusätzlichen Ladeoptionen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Ladeoptionen |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Neue Präsentation
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


Erstellt ein PresentationInfo-Objekt aus einer Datei und bindet die Präsentation daran.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Präsentationsdatei. |

**Rückgabe:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Präsentationsinformationen, die an die Präsentation gebunden sind.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPPresentationInfo getPresentationInfo(InputStream stream)
```


Erstellt ein PresentationInfo-Objekt aus einem Stream und bindet die Präsentation daran. Ruft Informationen über die Präsentation im angegebenen Stream ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Präsentationsstream. |

**Rückgabe:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Präsentationsinformationen, die an die Präsentation gebunden sind.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```


Liest eine vorhandene Präsentation aus einem Array

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Zu lesendes Array |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelesene Präsentation
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Liest eine vorhandene Präsentation aus einem Array mit zusätzlichen Ladeoptionen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Zu lesendes Array |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Ladeoptionen |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelesene Präsentation
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```


Liest eine vorhandene Präsentation aus einem Stream

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Einzulesender Eingabestream |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelesene Präsentation
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Liest eine vorhandene Präsentation aus einem Stream mit zusätzlichen Ladeoptionen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Einzulesender Eingabestream |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Ladeoptionen |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelesene Präsentation
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```


Liest eine vorhandene Präsentation aus einer Datei

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Dateiname |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelesene Präsentation
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```


Liest eine vorhandene Präsentation aus einem Stream mit zusätzlichen Ladeoptionen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Dateiname |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Ladeoptionen |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Gelesene Präsentation
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


Ruft den Rohtext aus den Folien ab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Eingabedatei |
| mode | int | Extraktionsmodus |

**Rückgabe:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Die Instanz von PresentationText, die das SlideText-Array mit dem Rohtext der Folien enthält
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


Ruft den Rohtext aus den Folien ab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Eingabestream |
| mode | int | Extraktionsmodus |

**Rückgabe:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Die Instanz von PresentationText, die das SlideText-Array mit dem Rohtext der Folien enthält
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Ruft den Rohtext aus den Folien ab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Eingabestream |
| mode | int | Extraktionsmodus |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Ladeoptionen |

**Rückgabe:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Die Instanz von PresentationText, die das SlideText-Array mit dem Rohtext der Folien enthält
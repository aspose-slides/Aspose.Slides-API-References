---
title: IPresentationFactory
second_title: Aspose.Slides für Android über Java API-Referenz
description: Ermöglicht das Erstellen einer Präsentation über die COM-Schnittstelle
type: docs
url: /de/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Ermöglicht das Erstellen einer Präsentation über die COM-Schnittstelle
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createPresentation()](#createPresentation--) | Erstellt eine neue Präsentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Erstellt eine neue Präsentation mit zusätzlichen Ladeoptionen |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Liefert Informationen zur Präsentation in der angegebenen Datei. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Liefert Informationen zur Präsentation im angegebenen Stream. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Liest eine vorhandene Präsentation aus einem Array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Liest eine vorhandene Präsentation aus einem Array mit zusätzlichen Ladeoptionen |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Liest eine vorhandene Präsentation aus einem Stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Liest eine vorhandene Präsentation aus einem Stream mit zusätzlichen Ladeoptionen |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Liest eine vorhandene Präsentation aus einer Datei |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Liest eine vorhandene Präsentation aus einem Stream mit zusätzlichen Ladeoptionen |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Ruft den Rohtext aus den Folien ab |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Ruft den Rohtext aus den Folien ab |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Ruft den Rohtext aus den Folien ab |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Erstellt eine neue Präsentation.

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Neue Präsentation
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
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
public abstract IPresentationInfo getPresentationInfo(String file)
```

Liefert Informationen zur Präsentation in der angegebenen Datei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Präsentationsdatei. |

**Rückgabe:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Präsentationsinformationen
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Liefert Informationen zur Präsentation im angegebenen Stream.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Präsentationsstream. |

**Rückgabe:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Präsentationsinformationen.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

Liest eine vorhandene Präsentation aus einem Array

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Array zum Lesen |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Geladene Präsentation
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Liest eine vorhandene Präsentation aus einem Array mit zusätzlichen Ladeoptionen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Array zum Lesen |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Ladeoptionen |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Geladene Präsentation
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Liest eine vorhandene Präsentation aus einem Stream

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Eingabestream zum Lesen |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Geladene Präsentation
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Liest eine vorhandene Präsentation aus einem Stream mit zusätzlichen Ladeoptionen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Eingabestream zum Lesen |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Ladeoptionen |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Geladene Präsentation
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Liest eine vorhandene Präsentation aus einer Datei

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Dateiname |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Geladene Präsentation
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Liest eine vorhandene Präsentation aus einer Datei mit zusätzlichen Ladeoptionen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Dateiname |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Ladeoptionen |

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation) - Geladene Präsentation
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

Ruft den Rohtext aus den Folien ab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | java.lang.String | Eingabedatei |
| mode | int | Extraktionsmodus |

**Rückgabe:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Die Instanz von PresentationText, die das SlideText-Array enthält, das den Rohtext der Folien repräsentiert
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

Ruft den Rohtext aus den Folien ab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Eingabestream |
| mode | int | Extraktionsmodus |

**Rückgabe:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Die Instanz von PresentationText, die das SlideText-Array enthält, das den Rohtext der Folien repräsentiert
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Ruft den Rohtext aus den Folien ab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Eingabestream |
| mode | int | Extraktionsmodus |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Ladeoptionen |

**Rückgabe:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Die Instanz von PresentationText, die das SlideText-Array enthält, das den Rohtext der Folien repräsentiert
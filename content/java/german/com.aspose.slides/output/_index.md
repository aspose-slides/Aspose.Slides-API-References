---
title: Output
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Ausgabeelementen für IWebDocument dar.
type: docs
url: /de/com.aspose.slides/output/
---
**Vererbung:**  
java.lang.Object  
```
public final class Output
```

Stellt eine Sammlung von Ausgabeelementen für IWebDocument dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Fügt ein Ausgabeelement für das Kontextobjekt hinzu. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Fügt ein Ausgabeelement für das Bild hinzu. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Fügt ein Ausgabeelement für das Bild hinzu. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Fügt ein Ausgabeelement für das Video hinzu. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Fügt ein Ausgabeelement für das Audio hinzu. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Erstellt und fügt ein Ausgabedateielement für die angegebene Schriftart hinzu. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Fügt ein Ausgabeelement für den Textinhalt hinzu. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Bindet Ressource an Ausgabedatei. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Gibt den Pfad für eine gegebene Ressource zurück. |

### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Fügt ein Ausgabeelement für das Kontextobjekt hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | java.lang.String | Ausgabepfad. |
| templateKey | java.lang.String | Der Schlüssel der Vorlage, die für die Transformation des Kontextobjekts vor der Ausgabe verwendet wird. |
| contextObject | TContextObject | Kontextobjekt. |

**Rückgabewert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) Objekt für das Kontextobjekt.

### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Fügt ein Ausgabeelement für das Bild hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | java.lang.String | Ausgabepfad. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das auszugebende Bild. |

**Rückgabewert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) Objekt für das Bild.

### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Fügt ein Ausgabeelement für das Bild hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | java.lang.String | Ausgabepfad. |
| image | [IImage](../../com.aspose.slides/iimage) | Das auszugebende Bild. |

**Rückgabewert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) Objekt für das Bild.

### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Fügt ein Ausgabeelement für das Video hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | java.lang.String | Ausgabepfad. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Das auszugebende Video. |

**Rückgabewert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) Objekt für das Video.

### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

Fügt ein Ausgabeelement für das Audio hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | java.lang.String | Ausgabepfad. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Das auszugebende Audio. |

**Rückgabewert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) Objekt für das Audio.

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Erstellt und fügt ein Ausgabedateielement für die angegebene Schriftart hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | java.lang.String | Der Dateipfad, an dem die Schriftartausgabe gespeichert wird. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Die Schriftartdaten, die in die Ausgabe geschrieben werden. |
| fontStyle | int | Der Stil der Schriftart (z. B. Regular, Bold, Italic). |

**Rückgabewert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Eine [IOutputFile](../../com.aspose.slides/ioutputfile) Instanz für die erzeugte Schriftart.

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Fügt ein Ausgabeelement für den Textinhalt hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | java.lang.String | Ausgabepfad. |
| textContent | java.lang.String | Auszugebender Inhalt. |

**Rückgabewert:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) Objekt für den Textinhalt.

### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Bindet Ressource an Ausgabedatei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Ausgabedatei. |
| obj | java.lang.Object | Ressourcenobjekt. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

Gibt den Pfad für eine gegebene Ressource zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ressourcenobjekt. |

**Rückgabewert:**
java.lang.String - Ressourcenpfad.
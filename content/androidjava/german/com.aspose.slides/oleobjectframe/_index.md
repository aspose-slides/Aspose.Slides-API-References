---
title: OleObjectFrame
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein OLE-Objekt auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/oleobjectframe/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Stellt ein OLE-Objekt auf einer Folie dar.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Lädt die PPTX in ein Präsentationsobjekt
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Greift auf die erste Folie zu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Wandelt die Form in OleObjectFrame um
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Liest das OLE-Objekt und schreibt es auf die Festplatte
>      if (oleObjectFrame != null) {
>          // Holt die eingebetteten Dateidaten
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Holt die Dateierweiterung der eingebetteten Datei
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Erstellt einen Pfad zum Speichern der extrahierten Datei
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Speichert die extrahierten Daten
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Gibt das OleObject-Bildfüllungs-Eigenschaftsobjekt zurück. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Gibt den Titel für das OleObject-Symbol zurück oder setzt ihn. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Gibt den Titel für das OleObject-Symbol zurück oder setzt ihn. |
| [getObjectName()](#getObjectName--) | Gibt den Namen eines Objekts zurück oder setzt ihn. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Gibt den Namen eines Objekts zurück oder setzt ihn. |
| [getObjectProgId()](#getObjectProgId--) | Gibt die ProgID eines Objekts zurück. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Gibt die ProgID eines Objekts zurück. |
| [getLinkFileName()](#getLinkFileName--) | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Gibt den relativen Pfad zu einer verknüpften Datei zurück, falls vorhanden, sonst einen leeren String. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Gibt den Dateinamen des eingebetteten OLE-Objekts zurück |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Gibt den Pfad des eingebetteten OLE-Objekts zurück |
| [getEmbeddedData()](#getEmbeddedData--) | Gibt Informationen über OLE-eingebettete Daten zurück oder setzt sie. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Setzt Informationen über OLE-eingebettete Daten. |
| [isObjectIcon()](#isObjectIcon--) | Bestimmt, ob ein Objekt als Symbol sichtbar ist. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Bestimmt, ob ein Objekt als Symbol sichtbar ist. |
| [isObjectLink()](#isObjectLink--) | Bestimmt, ob ein Objekt mit einer externen Datei verknüpft ist. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Gibt das OleObject-Bildfüllungs-Eigenschaftsobjekt zurück. Nur lesend [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Rückgabe:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Gibt den Titel für das OleObject-Symbol zurück oder setzt ihn. Lesen/Schreiben String.

--------------------

Wenn IsObjectIcon == false, wird dieser Wert ignoriert. Der String kann je nach Größe des Ole-Icons abgeschnitten werden.

**Rückgabe:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Gibt den Titel für das OleObject-Symbol zurück oder setzt ihn. Lesen/Schreiben String.

--------------------

Wenn IsObjectIcon == false, wird dieser Wert ignoriert. Der String kann je nach Größe des Ole-Icons abgeschnitten werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Gibt den Namen eines Objekts zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Gibt den Namen eines Objekts zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Gibt die ProgID eines Objekts zurück. Nur lesend String.

**Rückgabe:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Gibt die ProgID eines Objekts zurück. Nur lesend String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Kurzdateiname wird verwendet. Nur lesend String.

**Rückgabe:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Langdateiname wird verwendet. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Langdateiname wird verwendet. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Gibt den relativen Pfad zu einer verknüpften Datei zurück, falls vorhanden, sonst einen leeren String. Nur lesend String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

In PPT-Präsentationen können einige Ole-Objektverknüpfungen eine relative Darstellung aufweisen.

**Rückgabe:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

Gibt den Dateinamen des eingebetteten OLE-Objekts zurück

**Rückgabe:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Gibt den Pfad des eingebetteten OLE-Objekts zurück

**Rückgabe:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Gibt Informationen über OLE-eingebettete Daten zurück oder setzt sie. Lesen/Schreiben [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Rückgabe:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Setzt Informationen über OLE-eingebettete Daten.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Eingebettete Daten [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Diese Methode ändert die Eigenschaften des Objekts, um die neuen Daten widerzuspiegeln, und setzt das IsObjectLink-Flag auf false, wodurch das OLE-Objekt eingebettet wird. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Bestimmt, ob ein Objekt als Symbol sichtbar ist. Lesen/Schreiben boolean .

**Rückgabe:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Bestimmt, ob ein Objekt als Symbol sichtbar ist. Lesen/Schreiben boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Bestimmt, ob ein Objekt mit einer externen Datei verknüpft ist. Nur lesend boolean .

**Rückgabe:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. Lesen/Schreiben boolean .

**Rückgabe:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. Lesen/Schreiben boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
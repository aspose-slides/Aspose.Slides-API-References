---
title: IOleObjectFrame
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt ein OLE-Objekt auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/ioleobjectframe/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Stellt ein OLE-Objekt auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Gibt das OleObject Bildfüll-Eigenschaften-Objekt zurück. |
| [getObjectName()](#getObjectName--) | Gibt den Namen eines Objekts zurück oder setzt ihn. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Gibt den Namen eines Objekts zurück oder setzt ihn. |
| [getEmbeddedData()](#getEmbeddedData--) | Erhält Informationen über OLE-eingebettete Daten. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Setzt Informationen über OLE-eingebettete Daten. |
| [getObjectProgId()](#getObjectProgId--) | Gibt die ProgID eines Objekts zurück. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Gibt die ProgID eines Objekts zurück. |
| [getLinkFileName()](#getLinkFileName--) | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Gibt den relativen Pfad zu einer verknüpften Datei zurück, falls vorhanden, andernfalls wird ein leerer String zurückgegeben. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Gibt den Dateinamen des eingebetteten OLE-Objekts zurück |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Gibt den Pfad des eingebetteten OLE-Objekts zurück |
| [isObjectIcon()](#isObjectIcon--) | Bestimmt, ob ein Objekt als Symbol sichtbar ist. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Bestimmt, ob ein Objekt als Symbol sichtbar ist. |
| [isObjectLink()](#isObjectLink--) | Bestimmt, ob ein Objekt mit einer externen Datei verknüpft ist. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Gibt den Titel für das OleObject-Symbol zurück oder setzt ihn. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Gibt den Titel für das OleObject-Symbol zurück oder setzt ihn. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Gibt das OleObject Bildfüll-Eigenschaften-Objekt zurück. Nur lesbar [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Rückgabe:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Gibt den Namen eines Objekts zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Gibt den Namen eines Objekts zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Erhält Informationen über OLE-eingebettete Daten. Nur lesbar [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Rückgabe:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Setzt Informationen über OLE-eingebettete Daten.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
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

Diese Methode ändert die Eigenschaften des Objekts, um die neuen Daten widerzuspiegeln, und setzt das IsObjectLink-Flag auf false, was bedeutet, dass das OLE-Objekt eingebettet ist. |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Gibt die ProgID eines Objekts zurück. Nur lesbarer String.

**Rückgabe:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Gibt die ProgID eines Objekts zurück. Nur lesbarer String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Der Kurzdateiname wird verwendet. Nur lesbarer String.

**Rückgabe:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Der Langdateiname wird verwendet. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Gibt den vollständigen Pfad zu einer verknüpften Datei zurück. Der Langdateiname wird verwendet. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Gibt den relativen Pfad zu einer verknüpften Datei zurück, falls vorhanden, andernfalls wird ein leerer String zurückgegeben. Nur lesbarer String.

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

In den Ppt-Präsentationen können einige Ole-Objekt-Links eine relative Darstellung haben.

**Rückgabe:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Gibt den Dateinamen des eingebetteten OLE-Objekts zurück.

**Rückgabe:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Gibt den Pfad des eingebetteten OLE-Objekts zurück.

**Rückgabe:**
java.lang.String

### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Bestimmt, ob ein Objekt als Symbol sichtbar ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Bestimmt, ob ein Objekt als Symbol sichtbar ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Bestimmt, ob ein Objekt mit einer externen Datei verknüpft ist. Nur lesbarer boolean.

**Rückgabe:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Bestimmt, ob das verknüpfte eingebettete Objekt automatisch aktualisiert wird, wenn die Präsentation geöffnet oder gedruckt wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Gibt den Titel für das OleObject-Symbol zurück oder setzt ihn. Lesen/Schreiben String.

--------------------

Wenn IsObjectIcon == false, wird dieser Wert ignoriert. Der String kann je nach Größe des OLE-Symbols abgeschnitten werden.

**Rückgabe:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

Gibt den Titel für das OleObject-Symbol zurück oder setzt ihn. Lesen/Schreiben String.

--------------------

Wenn IsObjectIcon == false, wird dieser Wert ignoriert. Der String kann je nach Größe des OLE-Symbols abgeschnitten werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
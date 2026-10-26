---
title: OleObjectFrame
second_title: Aspose.Slides for Java API Referencia
description: Egy dián lévő OLE objektumot képvisel.
type: docs
url: /hu/com.aspose.slides/oleobjectframe/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Egy dián lévő OLE objektumot képvisel.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan lehet OLE objektum keretekhez hozzáférni.
>  
>  // Betölti a PPTX-et egy prezentáció objektumba
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Eléri az első diát
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Átkonvertálja az alakzatot OleObjectFrame-re
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Beolvassa az OLE objektumot és leírja a lemezre
>      if (oleObjectFrame != null) {
>          // Lekéri a beágyazott fájl adatát
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Lekéri a beágyazott fájl kiterjesztését
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Létrehozza az elérési utat a kinyert fájl mentéséhez
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Mentse a kinyert adatokat
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Visszaadja az OleObject képkitöltési tulajdonságok objektumát. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Visszaadja vagy beállítja az OleObject ikon címét. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Visszaadja vagy beállítja az OleObject ikon címét. |
| [getObjectName()](#getObjectName--) | Visszaadja vagy beállítja egy objektum nevét. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Visszaadja vagy beállítja egy objektum nevét. |
| [getObjectProgId()](#getObjectProgId--) | Visszaadja egy objektum ProgID-jét. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Visszaadja egy objektum ProgID-jét. |
| [getLinkFileName()](#getLinkFileName--) | Visszaadja a hivatkozott fájl teljes útvonalát. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja a hivatkozott fájl teljes útvonalát. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja a hivatkozott fájl teljes útvonalát. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Visszaadja a hivatkozott fájl relatív útvonalát, ha létezik, ellenkező esetben üres karakterláncot ad vissza. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Visszaadja a beágyazott OLE objektum fájlnevét |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Visszaadja a beágyazott OLE objektum útvonalát |
| [getEmbeddedData()](#getEmbeddedData--) | Lekérdezi vagy beállítja az OLE beágyazott adatokról szóló információkat. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Beállítja az OLE beágyazott adatokról szóló információkat. |
| [isObjectIcon()](#isObjectIcon--) | Megállapítja, hogy egy objektum ikonként látható-e. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Megállapítja, hogy egy objektum ikonként látható-e. |
| [isObjectLink()](#isObjectLink--) | Megállapítja, hogy egy objektum külső fájlra hivatkozik-e. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e, amikor a prezentáció megnyílik vagy nyomtatásra kerül. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e, amikor a prezentáció megnyílik vagy nyomtatásra kerül. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Visszaadja az OleObject képkitöltési tulajdonságok objektumát. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatér:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Visszaadja vagy beállítja az OleObject ikon címét. Olvasás/írás String.

--------------------

Ha az IsObjectIcon == false, akkor ez az érték figyelmen kívül marad. A karakterlánc a Ole ikon méretéhez igazítható.

**Visszatér:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Visszaadja vagy beállítja az OleObject ikon címét. Olvasás/írás String.

--------------------

Ha az IsObjectIcon == false, akkor ez az érték figyelmen kívül marad. A karakterlánc a Ole ikon méretéhez igazítható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Visszaadja vagy beállítja egy objektum nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Visszaadja vagy beállítja egy objektum nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Visszaadja egy objektum ProgID-jét. Csak olvasható String.

**Visszatér:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Visszaadja egy objektum ProgID-jét. Csak olvasható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Visszaadja a hivatkozott fájl teljes útvonalát. Rövid fájlnév lesz használva. Csak olvasható String.

**Visszatér:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Visszaadja a hivatkozott fájl teljes útvonalát. Hosszú fájlnév lesz használva. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Visszaadja a hivatkozott fájl teljes útvonalát. Hosszú fájlnév lesz használva. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Visszaadja a hivatkozott fájl relatív útvonalát, ha létezik, ellenkező esetben üres karakterláncot ad vissza. Csak olvasható String.

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

A Ppt prezentációkban néhány Ole objektum hivatkozás relatív ábrázolással rendelkezhet.

**Visszatér:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

Visszaadja a beágyazott OLE objektum fájlnevét

**Visszatér:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Visszaadja a beágyazott OLE objektum útvonalát

**Visszatér:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Lekérdezi vagy beállítja az OLE beágyazott adatokkal kapcsolatos információkat. Olvasás/írás [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Visszatér:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Beállítja az OLE beágyazott adatokkal kapcsolatos információkat.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Beágyazott adat [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Ez a metódus módosítja az objektum tulajdonságait az új adat tükrözésére, és a IsObjectLink jelzőt false-ra állítja, jelezve, hogy az OLE objektum be van ágyazva. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Megállapítja, hogy egy objektum ikonként látható-e. Olvasás/írás  boolean .

**Visszatér:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Megállapítja, hogy egy objektum ikonként látható-e. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Megállapítja, hogy egy objektum külső fájlra hivatkozik-e. Csak olvasható  boolean .

**Visszatér:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e, amikor a prezentáció megnyílik vagy nyomtatásra kerül. Olvasás/írás  boolean .

**Visszatér:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e, amikor a prezentáció megnyílik vagy nyomtatásra kerül. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
---
title: OleObjectFrame
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: OLE objektumot képvisel egy dián.
type: docs
url: /hu/com.aspose.slides/oleobjectframe/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

OLE objektumot képvisel egy dián.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Betölti a PPTX fájlt egy prezentáció objektumba
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Eléri az első diát
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Átkonvertálja a formát OleObjectFrame-re
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Beolvassa az OLE objektumot és lemezre írja
>      if (oleObjectFrame != null) {
>          // Lekéri a beágyazott fájl adatát
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Lekéri a beágyazott fájl kiterjesztését
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Létrehoz egy elérési utat a kicsomagolt fájl mentéséhez
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Mentse a kicsomagolt adatokat
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

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Visszaadja az OleObject képkitöltés tulajdonság objektumát. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Visszaadja vagy beállítja az OleObject ikon címét. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Visszaadja vagy beállítja az OleObject ikon címét. |
| [getObjectName()](#getObjectName--) | Visszaadja vagy beállítja egy objektum nevét. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Visszaadja vagy beállítja egy objektum nevét. |
| [getObjectProgId()](#getObjectProgId--) | Visszaadja egy objektum ProgID-jét. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Visszaadja egy objektum ProgID-jét. |
| [getLinkFileName()](#getLinkFileName--) | Visszaadja a linkelt fájl teljes útvonalát. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja a linkelt fájl teljes útvonalát. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja a linkelt fájl teljes útvonalát. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Visszaadja a linkelt fájl relatív útvonalát, ha létezik, egyébként üres karakterláncot ad vissza. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Visszaadja a beágyazott OLE objektum fájlnevét |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Visszaadja a beágyazott OLE objektum útvonalát |
| [getEmbeddedData()](#getEmbeddedData--) | Lekérdezi vagy beállítja az OLE beágyazott adatokra vonatkozó információkat. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Beállítja az OLE beágyazott adatokra vonatkozó információkat. |
| [isObjectIcon()](#isObjectIcon--) | Megállapítja, hogy egy objektum ikonként látható-e. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Megállapítja, hogy egy objektum ikonként látható-e. |
| [isObjectLink()](#isObjectLink--) | Megállapítja, hogy egy objektum külső fájlhoz kapcsolódik-e. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Megállapítja, hogy a linkelt beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Megállapítja, hogy a linkelt beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Visszaadja az OleObject képkitöltés tulajdonság objektumát. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatér:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Visszaadja vagy beállítja az OleObject ikon címét. Olvasás/írás String.

--------------------

Ha az IsObjectIcon == false, ez az érték figyelmen kívül marad. A karakterlánc a Ole ikon mérete szerint csonkolható.

**Visszatér:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Visszaadja vagy beállítja az OleObject ikon címét. Olvasás/írás String.

--------------------

Ha az IsObjectIcon == false, ez az érték figyelmen kívül marad. A karakterlánc a Ole ikon mérete szerint csonkolható.

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

Visszaadja a linkelt fájl teljes útvonalát. Rövid fájlnév lesz használva. Csak olvasható String.

**Visszatér:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Visszaadja a linkelt fájl teljes útvonalát. Hosszú fájlnév lesz használva. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Visszaadja a linkelt fájl teljes útvonalát. Hosszú fájlnév lesz használva. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Visszaadja a linkelt fájl relatív útvonalát, ha létezik, egyébként üres karakterláncot ad vissza. Csak olvasható String.

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

A Ppt prezentációkban egyes Ole objektum hivatkozások relatív ábrázolással rendelkezhetnek.

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

Lekérdezi vagy beállítja az OLE beágyazott adatokra vonatkozó információkat. Olvasás/írás [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Visszatér:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Beállítja az OLE beágyazott adatokra vonatkozó információkat.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

Ez a metódus módosítja az objektum tulajdonságait az új adatok tükrözésére, és az IsObjectLink jelzőt false-ra állítja, jelezve, hogy az OLE objektum be van ágyazva. |

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

Megállapítja, hogy egy objektum külső fájlhoz kapcsolódik-e. Csak olvasható  boolean .

**Visszatér:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Megállapítja, hogy a linkelt beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. Olvasás/írás  boolean .

**Visszatér:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Megállapítja, hogy a linkelt beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
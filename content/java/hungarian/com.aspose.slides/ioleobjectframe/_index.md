---
title: IOleObjectFrame
second_title: Aspose.Slides Java API referenciája
description: Egy dián lévő OLE objektumot képvisel.
type: docs
url: /hu/com.aspose.slides/ioleobjectframe/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Egy dián lévő OLE objektumot reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Visszaadja az OleObject kép kitöltési tulajdonságok objektumot. |
| [getObjectName()](#getObjectName--) | Visszaadja vagy beállítja egy objektum nevét. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Visszaadja vagy beállítja egy objektum nevét. |
| [getEmbeddedData()](#getEmbeddedData--) | Lekérdezi az OLE beágyazott adatokról szóló információkat. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Beállítja az OLE beágyazott adatokkal kapcsolatos információkat. |
| [getObjectProgId()](#getObjectProgId--) | Visszaadja egy objektum ProgID-jét. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Visszaadja egy objektum ProgID-jét. |
| [getLinkFileName()](#getLinkFileName--) | Visszaadja a hivatkozott fájl teljes útvonalát. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja a hivatkozott fájl teljes útvonalát. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja a hivatkozott fájl teljes útvonalát. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Visszaadja a hivatkozott fájl relatív útvonalát, ha létezik, egyébként egy üres karakterláncot ad vissza. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Visszaadja a beágyazott OLE objektum fájlnevét |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Visszaadja a beágyazott OLE objektum útvonalát |
| [isObjectIcon()](#isObjectIcon--) | Meghatározza, hogy egy objektum ikonként látható-e. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Meghatározza, hogy egy objektum ikonként látható-e. |
| [isObjectLink()](#isObjectLink--) | Meghatározza, hogy egy objektum külső fájlhoz van-e kapcsolva. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Meghatározza, hogy a hivatkozott beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Meghatározza, hogy a hivatkozott beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Visszaadja vagy beállítja az OleObject ikon címét. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Visszaadja vagy beállítja az OleObject ikon címét. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Visszaadja az OleObject kép kitöltési tulajdonságok objektumot. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatérési érték:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Visszaadja vagy beállítja egy objektum nevét. Olvasható/írható String.

**Visszatérési érték:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Visszaadja vagy beállítja egy objektum nevét. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Lekérdezi az OLE beágyazott adatokra vonatkozó információkat. Csak olvasható [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Visszatérési érték:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Beállítja az OLE beágyazott adatokkal kapcsolatos információkat.

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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Ez a metódus módosítja az objektum tulajdonságait az új adatok tükrözésére, és a IsObjectLink jelzőt hamisra állítja, jelezve, hogy az OLE objektum beágyazott.

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Visszaadja egy objektum ProgID-jét. Csak olvasható String.

**Visszatérési érték:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Visszaadja egy objektum ProgID-jét. Csak olvasható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Visszaadja a hivatkozott fájl teljes útvonalát. Rövid fájlnév lesz használva. Csak olvasható String.

**Visszatérési érték:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Visszaadja a hivatkozott fájl teljes útvonalát. Hosszú fájlnév lesz használva. Olvasható/írható String.

**Visszatérési érték:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Visszaadja a hivatkozott fájl teljes útvonalát. Hosszú fájlnév lesz használva. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Visszaadja a hivatkozott fájl relatív útvonalát, ha létezik, egyébként egy üres karakterláncot ad vissza. Csak olvasható String.

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

A Ppt prezentációkban egyes Ole objektum hivatkozások relatív ábrázolást is tartalmazhatnak.

**Visszatérési érték:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Visszaadja a beágyazott OLE objektum fájlnevét

**Visszatérési érték:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Visszaadja a beágyazott OLE objektum útvonalát

**Visszatérési érték:**
java.lang.String

### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Meghatározza, hogy egy objektum ikonként látható-e. Olvasható/írható boolean.

**Visszatérési érték:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Meghatározza, hogy egy objektum ikonként látható-e. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Meghatározza, hogy egy objektum külső fájlhoz van-e kapcsolva. Csak olvasható boolean.

**Visszatérési érték:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Meghatározza, hogy a hivatkozott beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. Olvasható/írható boolean.

**Visszatérési érték:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Meghatározza, hogy a hivatkozott beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Visszaadja vagy beállítja az OleObject ikon címét. Olvasható/írható String.

--------------------

Amikor az IsObjectIcon == false, ez az érték figyelmen kívül marad. A karakterlánc a OLE ikon mérete szerint csonkolható.

**Visszatérési érték:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

Visszaadja vagy beállítja az OleObject ikon címét. Olvasható/írható String.

--------------------

Amikor az IsObjectIcon == false, ez az érték figyelmen kívül marad. A karakterlánc a OLE ikon mérete szerint csonkolható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
---
title: IOleObjectFrame
second_title: Aspose.Slides for Android Java API referencia
description: OLE objektumot képvisel egy dián.
type: docs
url: /hu/com.aspose.slides/ioleobjectframe/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

OLE objektumot képvisel egy dián.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Visszaadja az OleObject képkitöltés tulajdonság objektumot. |
| [getObjectName()](#getObjectName--) | Visszaadja vagy beállítja egy objektum nevét. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Visszaadja vagy beállítja egy objektum nevét. |
| [getEmbeddedData()](#getEmbeddedData--) | Lekéri az OLE beágyazott adatokról szóló információt. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Beállítja az OLE beágyazott adatokról szóló információt. |
| [getObjectProgId()](#getObjectProgId--) | Visszaadja egy objektum ProgID-jét. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Visszaadja egy objektum ProgID-jét. |
| [getLinkFileName()](#getLinkFileName--) | Visszaadja a hivatkozott fájl teljes elérési útját. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja a hivatkozott fájl teljes elérési útját. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja a hivatkozott fájl teljes elérési útját. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Visszaadja a hivatkozott fájl relatív útvonalát, ha létezik, egyébként üres karakterláncot ad vissza. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Visszaadja a beágyazott OLE objektum fájlnevet |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Visszaadja a beágyazott OLE objektum útvonalát |
| [isObjectIcon()](#isObjectIcon--) | Megállapítja, hogy egy objektum ikonként látható-e. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Megállapítja, hogy egy objektum ikonként látható-e. |
| [isObjectLink()](#isObjectLink--) | Megállapítja, hogy egy objektum külső fájlra hivatkozik-e. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e, amikor a prezentáció megnyílik vagy nyomtatásra kerül. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e, amikor a prezentáció megnyílik vagy nyomtatásra kerül. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Visszaadja vagy beállítja az OleObject ikon címét. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Visszaadja vagy beállítja az OleObject ikon címét. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Visszaadja az OleObject képkitöltés tulajdonság objektumot. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatér:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```


Visszaadja vagy beállítja egy objektum nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


Visszaadja vagy beállítja egy objektum nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


Lekéri az OLE beágyazott adatokról szóló információt. Csak olvasás [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Visszatér:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


Beállítja az OLE beágyazott adatokról szóló információt.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Beágyazott adat [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Ez a metódus módosítja az objektum tulajdonságait az új adatoknak megfelelően, és a IsObjectLink jelzőt hamisra állítja, jelezve, hogy az OLE objektum beágyazott. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```


Visszaadja egy objektum ProgID-jét. Csak olvasás String.

**Visszatér:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```


Visszaadja egy objektum ProgID-jét. Csak olvasás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


Visszaadja a hivatkozott fájl teljes elérési útját. Rövid fájlnév lesz használva. Csak olvasható String.

**Visszatér:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Visszaadja a hivatkozott fájl teljes elérési útját. Hosszú fájlnév lesz használva. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Visszaadja a hivatkozott fájl teljes elérési útját. Hosszú fájlnév lesz használva. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```


Visszaadja a hivatkozott fájl relatív útvonalát, ha létezik, egyébként üres karakterláncot ad vissza. Csak olvasható String.

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

A PPT prezentációkban néhány Ole objektum hivatkozás relatív ábrázolást tartalmazhat.

**Visszatér:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```


Visszaadja a beágyazott OLE objektum fájlnevet

**Visszatér:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```


Visszaadja a beágyazott OLE objektum útvonalát

**Visszatér:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```


Megállapítja, hogy egy objektum ikonként látható-e. Olvasás/írás boolean.

**Visszatér:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```


Megállapítja, hogy egy objektum ikonként látható-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```


Megállapítja, hogy egy objektum külső fájlra hivatkozik-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e, amikor a prezentáció megnyílik vagy nyomtatásra kerül. Olvasás/írás boolean.

**Visszatér:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


Megállapítja, hogy a hivatkozott beágyazott objektum automatikusan frissül-e, amikor a prezentáció megnyílik vagy nyomtatásra kerül. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


Visszaadja vagy beállítja az OleObject ikon címét. Olvasás/írás String.

--------------------

Ha az IsObjectIcon == false, ezt az értéket figyelmen kívül hagyják. A karakterlánc az OLE ikon mérete szerint csonkolható.

**Visszatér:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


Visszaadja vagy beállítja az OleObject ikon címét. Olvasás/írás String.

--------------------

Ha az IsObjectIcon == false, ezt az értéket figyelmen kívül hagyják. A karakterlánc az OLE ikon mérete szerint csonkolható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
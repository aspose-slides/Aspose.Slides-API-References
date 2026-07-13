---
title: IOleObjectFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett OLE-objekt på en bild.
type: docs
url: /sv/com.aspose.slides/ioleobjectframe/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Representerar ett OLE-objekt på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returnerar OleObject bildfyllningsegenskapsobjekt. |
| [getObjectName()](#getObjectName--) | Returnerar eller anger namnet på ett objekt. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Returnerar eller anger namnet på ett objekt. |
| [getEmbeddedData()](#getEmbeddedData--) | Hämtar information om OLE inbäddade data. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Anger information om OLE inbäddade data. |
| [getObjectProgId()](#getObjectProgId--) | Returnerar ProgID för ett objekt. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Returnerar ProgID för ett objekt. |
| [getLinkFileName()](#getLinkFileName--) | Returnerar den fullständiga sökvägen till en länkad fil. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar den fullständiga sökvägen till en länkad fil. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar den fullständiga sökvägen till en länkad fil. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Returnerar den relativa sökvägen till en länkad fil om den finns, annars returneras en tom sträng. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Returnerar filnamnet för inbäddat OLE-objekt. |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Returnerar sökvägen för inbäddat OLE-objekt. |
| [isObjectIcon()](#isObjectIcon--) | Bestämmer om ett objekt är synligt som ikon. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Bestämmer om ett objekt är synligt som ikon. |
| [isObjectLink()](#isObjectLink--) | Bestämmer om ett objekt är länkat till en extern fil. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Bestämmer om det länkade inbäddade objektet uppdateras automatiskt när presentationen öppnas eller skrivs ut. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Bestämmer om det länkade inbäddade objektet uppdateras automatiskt när presentationen öppnas eller skrivs ut. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Returnerar eller anger titeln för OleObject-ikon. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Returnerar eller anger titeln för OleObject-ikon. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Returnerar OleObject bildfyllningsegenskapsobjekt. Skrivskyddad [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returnerar:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Returnerar eller anger namnet på ett objekt. Läs/skriv String.

**Returnerar:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Returnerar eller anger namnet på ett objekt. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Hämtar information om OLE inbäddade data. Skrivskyddad [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Returnerar:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Anger information om OLE inbäddade data.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Inbäddade data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

Denna metod ändrar objektets egenskaper för att återspegla de nya data och sätter flaggan IsObjectLink till false, vilket indikerar att OLE-objektet är inbäddat. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Returnerar ProgID för ett objekt. Skrivskyddad String.

**Returnerar:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Returnerar ProgID för ett objekt. Skrivskyddad String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Returnerar den fullständiga sökvägen till en länkad fil. Kort filnamn kommer att användas. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Returnerar den fullständiga sökvägen till en länkad fil. Långt filnamn kommer att användas. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Returnerar den fullständiga sökvägen till en länkad fil. Långt filnamn kommer att användas. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Returnerar den relativa sökvägen till en länkad fil om den finns, annars returneras en tom sträng. Skrivskyddad String.

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

I Ppt-presentationer kan vissa Ole-objektlänkar ha en relativ representation.

**Returnerar:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Returnerar filnamnet för inbäddat OLE-objekt

**Returnerar:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Returnerar sökvägen för inbäddat OLE-objekt

**Returnerar:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Bestämmer om ett objekt är synligt som ikon. Läs/skriv boolean.

**Returnerar:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Bestämmer om ett objekt är synligt som ikon. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Bestämmer om ett objekt är länkat till en extern fil. Skrivskyddad boolean.

**Returnerar:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Bestämmer om det länkade inbäddade objektet uppdateras automatiskt när presentationen öppnas eller skrivs ut. Läs/skriv boolean.

**Returnerar:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Bestämmer om det länkade inbäddade objektet uppdateras automatiskt när presentationen öppnas eller skrivs ut. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Returnerar eller anger titeln för OleObject-ikon. Läs/skriv String.

--------------------

När IsObjectIcon == false ignoreras detta värde. Strängen kan trunkeras enligt storleken på OLE-ikonen.

**Returnerar:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

Returnerar eller anger titeln för OleObject-ikon. Läs/skriv String.

--------------------

När IsObjectIcon == false ignoreras detta värde. Strängen kan trunkeras enligt storleken på OLE-ikonen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
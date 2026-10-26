---
title: OleObjectFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett OLE-objekt på en bild.
type: docs
url: /sv/com.aspose.slides/oleobjectframe/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Representerar ett OLE-objekt på en bild.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Laddar PPTX till ett presentationsobjekt
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Hämtar den första bilden
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Konverterar formen till OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Läser OLE-objektet och skriver det till disk
>      if (oleObjectFrame != null) {
>          // Hämtar inbäddad fildata
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Hämtar inbäddad filändelse
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Skapar en sökväg för att spara den extraherade filen
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Sparar extraherade data
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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returnerar OleObject bildfyllningsegenskapsobjekt. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Returnerar eller anger titeln för OleObject-ikonen. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Returnerar eller anger titeln för OleObject-ikonen. |
| [getObjectName()](#getObjectName--) | Returnerar eller anger namnet på ett objekt. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Returnerar eller anger namnet på ett objekt. |
| [getObjectProgId()](#getObjectProgId--) | Returnerar ProgID för ett objekt. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Returnerar ProgID för ett objekt. |
| [getLinkFileName()](#getLinkFileName--) | Returnerar hela sökvägen till en länkad fil. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar hela sökvägen till en länkad fil. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar hela sökvägen till en länkad fil. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Returnerar den relativa sökvägen till en länkad fil om den finns, annars returneras en tom sträng. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Returnerar filnamnet för inbäddat OLE-objekt |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Returnerar sökvägen för inbäddat OLE-objekt |
| [getEmbeddedData()](#getEmbeddedData--) | Hämtar eller anger information om OLE-inbäddade data. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Anger information om OLE-inbäddade data. |
| [isObjectIcon()](#isObjectIcon--) | Avgör om ett objekt är synligt som ikon. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Avgör om ett objekt är synligt som ikon. |
| [isObjectLink()](#isObjectLink--) | Avgör om ett objekt är länkat till en extern fil. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Avgör om det länkade inbäddade objektet uppdateras automatiskt när presentationen öppnas eller skrivs ut. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Avgör om det länkade inbäddade objektet uppdateras automatiskt när presentationen öppnas eller skrivs ut. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Returnerar OleObject bildfyllningsegenskapsobjekt. Skrivskyddad [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returnerar:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Returnerar eller anger titeln för OleObject-ikonen. Läs/skriv String.

--------------------

När IsObjectIcon == false ignoreras detta värde. Strängen kan trunkeras enligt storleken på Ole-ikonen.

**Returnerar:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Returnerar eller anger titeln för OleObject-ikonen. Läs/skriv String.

--------------------

När IsObjectIcon == false ignoreras detta värde. Strängen kan trunkeras enligt storleken på Ole-ikonen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Returnerar eller anger namnet på ett objekt. Läs/skriv String.

**Returnerar:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Returnerar eller anger namnet på ett objekt. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Returnerar ProgID för ett objekt. Skrivskyddad String.

**Returnerar:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Returnerar ProgID för ett objekt. Skrivskyddad String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Returnerar hela sökvägen till en länkad fil. Kort filnamn kommer att användas. Skrivskyddad String.

**Returnerar:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Returnerar hela sökvägen till en länkad fil. Långt filnamn kommer att användas. Läs/skriv String.

**Returnerar:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Returnerar hela sökvägen till en länkad fil. Långt filnamn kommer att användas. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
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
public final String getEmbeddedFileLabel()
```

Returnerar filnamnet för inbäddat OLE-objekt

**Returnerar:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Returnerar sökvägen för inbäddat OLE-objekt

**Returnerar:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Hämtar eller anger information om OLE-inbäddade data. Läs/skriv [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Returnerar:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Anger information om OLE-inbäddade data.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Inbäddad data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

Denna metod ändrar objektets egenskaper för att återspegla den nya datan och sätter IsObjectLink-flaggan till false, vilket indikerar att OLE-objektet är inbäddat. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Avgör om ett objekt är synligt som ikon. Läs/skriv boolean .

**Returnerar:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Avgör om ett objekt är synligt som ikon. Läs/skriv boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Avgör om ett objekt är länkat till en extern fil. Skrivskyddad boolean .

**Returnerar:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Avgör om det länkade inbäddade objektet uppdateras automatiskt när presentationen öppnas eller skrivs ut. Läs/skriv boolean .

**Returnerar:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Avgör om det länkade inbäddade objektet uppdateras automatiskt när presentationen öppnas eller skrivs ut. Läs/skriv boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
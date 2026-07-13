---
title: OleObjectFrame
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een OLE-object op een dia voor.
type: docs
url: /nl/com.aspose.slides/oleobjectframe/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Stelt een OLE-object op een dia voor.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Laadt de PPTX naar een presentatieobject
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Toegang tot de eerste dia
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Cast het shape naar OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Leest het OLE Object en schrijft het naar de schijf
>      if (oleObjectFrame != null) {
>          // Haalt ingesloten bestandsgegevens op
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Haalt ingesloten bestands-extensie op
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Maakt een pad aan om het geëxtraheerde bestand op te slaan
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Slaat geëxtraheerde gegevens op
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

| Methode | Beschrijving |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Retourneert OleObject afbeeldingvulling-eigenschappenobject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Retourneert of stelt de titel voor OleObject-pictogram in. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Retourneert of stelt de titel voor OleObject-pictogram in. |
| [getObjectName()](#getObjectName--) | Retourneert of stelt de naam van een object in. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Retourneert of stelt de naam van een object in. |
| [getObjectProgId()](#getObjectProgId--) | Retourneert de ProgID van een object. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Retourneert de ProgID van een object. |
| [getLinkFileName()](#getLinkFileName--) | Retourneert het volledige pad naar een gekoppeld bestand. |
| [getLinkPathLong()](#getLinkPathLong--) | Retourneert het volledige pad naar een gekoppeld bestand. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retourneert het volledige pad naar een gekoppeld bestand. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Retourneert het relatieve pad naar een gekoppeld bestand indien aanwezig, anders een lege tekenreeks. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Retourneert de bestandsnaam van ingesloten OLE-object. |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Retourneert het pad van ingesloten OLE-object. |
| [getEmbeddedData()](#getEmbeddedData--) | Haalt op of stelt informatie over OLE-ingesloten gegevens in. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Stelt informatie over OLE-ingesloten gegevens in. |
| [isObjectIcon()](#isObjectIcon--) | Bepaalt of een object zichtbaar is als pictogram. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Bepaalt of een object zichtbaar is als pictogram. |
| [isObjectLink()](#isObjectLink--) | Bepaalt of een object gekoppeld is aan een extern bestand. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Bepaalt of het gekoppelde ingesloten object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Bepaalt of het gekoppelde ingesloten object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Retourneert OleObject afbeeldingvulling-eigenschappenobject. Alleen-lezen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retourneert:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Retourneert of stelt de titel voor OleObject-pictogram in. Lees-/schrijf String.

--------------------

Wanneer IsObjectIcon == false wordt deze waarde genegeerd. De tekenreeks kan worden afgekapt volgens de grootte van het Ole-pictogram.

**Retourneert:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Retourneert of stelt de titel voor OleObject-pictogram in. Lees-/schrijf String.

--------------------

Wanneer IsObjectIcon == false wordt deze waarde genegeerd. De tekenreeks kan worden afgekapt volgens de grootte van het Ole-pictogram.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Retourneert of stelt de naam van een object in. Lees-/schrijf String.

**Retourneert:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Retourneert of stelt de naam van een object in. Lees-/schrijf String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Retourneert de ProgID van een object. Alleen-lezen String.

**Retourneert:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Retourneert de ProgID van een object. Alleen-lezen String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Retourneert het volledige pad naar een gekoppeld bestand. Korte bestandsnaam zal worden gebruikt. Alleen-lezen String.

**Retourneert:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Retourneert het volledige pad naar een gekoppeld bestand. Lange bestandsnaam zal worden gebruikt. Lees-/schrijf String.

**Retourneert:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Retourneert het volledige pad naar een gekoppeld bestand. Lange bestandsnaam zal worden gebruikt. Lees-/schrijf String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Retourneert het relatieve pad naar een gekoppeld bestand indien aanwezig, anders een lege tekenreeks. Alleen-lezen String.

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

In de Ppt-presentaties kunnen sommige Ole-objectkoppelingen een relatieve representatie hebben.

**Retourneert:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

Retourneert de bestandsnaam van ingesloten OLE-object.

**Retourneert:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Retourneert het pad van ingesloten OLE-object.

**Retourneert:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Haalt op of stelt informatie over OLE-ingesloten gegevens in. Lees-/schrijf [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Retourneert:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Stelt informatie over OLE-ingesloten gegevens in.

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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Ingesloten gegevens [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

Deze methode wijzigt de eigenschappen van het object om de nieuwe gegevens weer te geven en zet de IsObjectLink-vlag op false, wat aangeeft dat het OLE-object is ingesloten. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Bepaalt of een object zichtbaar is als pictogram. Lees-/schrijf boolean.

**Retourneert:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Bepaalt of een object zichtbaar is als pictogram. Lees-/schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Bepaalt of een object gekoppeld is aan een extern bestand. Alleen-lezen boolean.

**Retourneert:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Bepaalt of het gekoppelde ingesloten object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. Lees-/schrijf boolean.

**Retourneert:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Bepaalt of het gekoppelde ingesloten object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. Lees-/schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
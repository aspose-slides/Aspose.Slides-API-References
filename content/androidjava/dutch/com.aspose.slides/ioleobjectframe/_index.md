---
title: IOleObjectFrame
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een OLE-object op een dia voor.
type: docs
url: /nl/com.aspose.slides/ioleobjectframe/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Stelt een OLE-object op een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Retourneert OleObject image fill properties object. |
| [getObjectName()](#getObjectName--) | Retourneert of stelt de naam van een object in. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Retourneert of stelt de naam van een object in. |
| [getEmbeddedData()](#getEmbeddedData--) | Haalt informatie over OLE embedded data op. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Stelt informatie over OLE embedded data in. |
| [getObjectProgId()](#getObjectProgId--) | Retourneert de ProgID van een object. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Retourneert de ProgID van een object. |
| [getLinkFileName()](#getLinkFileName--) | Retourneert het volledige pad naar een gekoppeld bestand. |
| [getLinkPathLong()](#getLinkPathLong--) | Retourneert het volledige pad naar een gekoppeld bestand. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retourneert het volledige pad naar een gekoppeld bestand. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Retourneert het relatieve pad naar een gekoppeld bestand indien aanwezig, anders een lege tekenreeks. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Retourneert de bestandsnaam van embedded OLE object |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Retourneert het pad van embedded OLE object |
| [isObjectIcon()](#isObjectIcon--) | Bepaalt of een object zichtbaar is als pictogram. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Bepaalt of een object zichtbaar is als pictogram. |
| [isObjectLink()](#isObjectLink--) | Bepaalt of een object is gekoppeld aan een extern bestand. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Bepaalt of het gekoppelde embedded object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Bepaalt of het gekoppelde embedded object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Retourneert of stelt de titel voor OleObject-pictogram in. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Retourneert of stelt de titel voor OleObject-pictogram in. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Retourneert OleObject image fill properties object. Alleen-lezen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retourneert:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Retourneert of stelt de naam van een object in. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Retourneert of stelt de naam van een object in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Haalt informatie over OLE embedded data op. Alleen-lezen [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Retourneert:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Stelt informatie over OLE embedded data in.

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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Ingesloten data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

Deze methode wijzigt de eigenschappen van het object om de nieuwe gegevens weer te geven en zet de IsObjectLink-vlag op false, wat aangeeft dat het OLE-object is ingesloten.

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Retourneert de ProgID van een object. Alleen-lezen String.

**Retourneert:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Retourneert de ProgID van een object. Alleen-lezen String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Retourneert het volledige pad naar een gekoppeld bestand. Korte bestandsnaam zal worden gebruikt. Alleen-lezen String.

**Retourneert:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Retourneert het volledige pad naar een gekoppeld bestand. Lange bestandsnaam zal worden gebruikt. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Retourneert het volledige pad naar een gekoppeld bestand. Lange bestandsnaam zal worden gebruikt. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
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

In de Ppt-presentaties kunnen sommige Ole-objectkoppelingen een relatieve weergave hebben.

**Retourneert:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Retourneert de bestandsnaam van embedded OLE object

**Retourneert:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Retourneert het pad van embedded OLE object

**Retourneert:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Bepaalt of een object zichtbaar is als pictogram. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Bepaalt of een object zichtbaar is als pictogram. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Bepaalt of een object is gekoppeld aan een extern bestand. Alleen-lezen boolean.

**Retourneert:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Bepaalt of het gekoppelde embedded object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Bepaalt of het gekoppelde embedded object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Retourneert of stelt de titel voor OleObject-pictogram in. Lezen/schrijven String.

--------------------

Wanneer IsObjectIcon == false wordt deze waarde genegeerd. De tekenreeks kan worden afgekapt volgens de grootte van het OLE-pictogram.

**Retourneert:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

Retourneert of stelt de titel voor OleObject-pictogram in. Lezen/schrijven String.

--------------------

Wanneer IsObjectIcon == false wordt deze waarde genegeerd. De tekenreeks kan worden afgekapt volgens de grootte van het OLE-pictogram.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
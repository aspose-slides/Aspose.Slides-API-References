---
title: IOleObjectFrame
second_title: Aspose.Slides pro Android pomocí Java API
description: Reprezentuje OLE objekt na snímku.
type: docs
url: /cs/com.aspose.slides/ioleobjectframe/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Představuje OLE objekt na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Vrací objekt vlastností výplně obrázku OleObject. |
| [getObjectName()](#getObjectName--) | Vrací nebo nastavuje název objektu. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Vrací nebo nastavuje název objektu. |
| [getEmbeddedData()](#getEmbeddedData--) | Získává informace o vložených OLE datech. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Nastavuje informace o vložených OLE datech. |
| [getObjectProgId()](#getObjectProgId--) | Vrací ProgID objektu. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Vrací ProgID objektu. |
| [getLinkFileName()](#getLinkFileName--) | Vrací úplnou cestu k propojenému souboru. |
| [getLinkPathLong()](#getLinkPathLong--) | Vrací úplnou cestu k propojenému souboru. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Vrací úplnou cestu k propojenému souboru. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Vrací relativní cestu k propojenému souboru, pokud existuje, jinak vrací prázdný řetězec. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Vrací název souboru vloženého OLE objektu |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Vrací cestu k vloženému OLE objektu |
| [isObjectIcon()](#isObjectIcon--) | Určuje, zda je objekt viditelný jako ikona. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Určuje, zda je objekt viditelný jako ikona. |
| [isObjectLink()](#isObjectLink--) | Určuje, zda je objekt propojen s externím souborem. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Určuje, zda je propojený vložený objekt automaticky aktualizován při otevření nebo tisku prezentace. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Určuje, zda je propojený vložený objekt automaticky aktualizován při otevření nebo tisku prezentace. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Vrací nebo nastavuje název ikony OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Vrací nebo nastavuje název ikony OleObject. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Vrací objekt vlastností výplně obrázku OleObject. Pouze pro čtení [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Vrací:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Vrací nebo nastavuje název objektu. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Vrací nebo nastavuje název objektu. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Získává informace o vložených OLE datech. Pouze pro čtení [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Vrací:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Nastavuje informace o vložených OLE datech.

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Vložená data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Tato metoda mění vlastnosti objektu tak, aby odrážely nová data, a nastaví příznak IsObjectLink na false, což značí, že OLE objekt je vložen. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Vrací ProgID objektu. Pouze pro čtení String.

**Vrací:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Vrací ProgID objektu. Pouze pro čtení String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Vrací úplnou cestu k propojenému souboru. Bude použito krátké jméno souboru. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Vrací úplnou cestu k propojenému souboru. Bude použito dlouhé jméno souboru. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Vrací úplnou cestu k propojenému souboru. Bude použito dlouhé jméno souboru. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Vrací relativní cestu k propojenému souboru, pokud existuje, jinak vrací prázdný řetězec. Pouze pro čtení String.

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

V prezentacích Ppt mohou některé odkazy na Ole objekty mít relativní reprezentaci.

**Vrací:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Vrací název souboru vloženého OLE objektu

**Vrací:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Vrací cestu k vloženému OLE objektu

**Vrací:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Určuje, zda je objekt viditelný jako ikona. Čtení/Zápis boolean.

**Vrací:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Určuje, zda je objekt viditelný jako ikona. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Určuje, zda je objekt propojen s externím souborem. Pouze pro čtení boolean.

**Vrací:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Určuje, zda je propojený vložený objekt automaticky aktualizován při otevření nebo tisku prezentace. Čtení/Zápis boolean.

**Vrací:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Určuje, zda je propojený vložený objekt automaticky aktualizován při otevření nebo tisku prezentace. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Vrací nebo nastavuje název ikony OleObject. Čtení/Zápis String.

--------------------

Když je IsObjectIcon == false, tato hodnota je ignorována. Řetězec může být zkrácen podle velikosti OLE ikony.

**Vrací:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

Vrací nebo nastavuje název ikony OleObject. Čtení/Zápis String.

--------------------

Když je IsObjectIcon == false, tato hodnota je ignorována. Řetězec může být zkrácen podle velikosti OLE ikony.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
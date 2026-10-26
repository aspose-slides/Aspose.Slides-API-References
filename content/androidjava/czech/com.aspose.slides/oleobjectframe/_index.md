---
title: OleObjectFrame
second_title: Aspose.Slides pro Android přes referenci Java API
description: Představuje OLE objekt na snímku.
type: docs
url: /cs/com.aspose.slides/oleobjectframe/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Představuje OLE objekt na snímku.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Načte PPTX do objektu prezentace
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Přistupuje k prvnímu snímku
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Přetypuje tvar na OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Načte OLE objekt a zapíše jej na disk
>      if (oleObjectFrame != null) {
>          // Získá data vloženého souboru
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Získá příponu vloženého souboru
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Vytvoří cestu pro uložení extrahovaného souboru
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Uloží extrahovaná data
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
## Metody

| Metoda | Popis |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Vrací objekt vlastností výplně obrázku OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Vrací nebo nastavuje titulek pro ikonu OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Vrací nebo nastavuje titulek pro ikonu OleObject. |
| [getObjectName()](#getObjectName--) | Vrací nebo nastavuje název objektu. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Vrací nebo nastavuje název objektu. |
| [getObjectProgId()](#getObjectProgId--) | Vrací ProgID objektu. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Vrací ProgID objektu. |
| [getLinkFileName()](#getLinkFileName--) | Vrací úplnou cestu k propojenému souboru. |
| [getLinkPathLong()](#getLinkPathLong--) | Vrací úplnou cestu k propojenému souboru. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Vrací úplnou cestu k propojenému souboru. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Vrací relativní cestu k propojenému souboru, pokud je přítomna, jinak vrací prázdný řetězec. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Vrací název souboru vloženého OLE objektu |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Vrací cestu vloženého OLE objektu |
| [getEmbeddedData()](#getEmbeddedData--) | Získává nebo nastavuje informace o vložených OLE datech. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Nastavuje informace o vložených OLE datech. |
| [isObjectIcon()](#isObjectIcon--) | Určuje, zda je objekt viditelný jako ikona. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Určuje, zda je objekt viditelný jako ikona. |
| [isObjectLink()](#isObjectLink--) | Určuje, zda je objekt propojen s externím souborem. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Určuje, zda je propojený vložený objekt automaticky aktualizován při otevření nebo tisku prezentace. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Určuje, zda je propojený vložený objekt automaticky aktualizován při otevření nebo tisku prezentace. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Vrací objekt vlastností výplně obrázku OleObject. Pouze pro čtení [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Vrací:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Vrací nebo nastavuje titulek pro ikonu OleObject. Čtení/Zápis String.

--------------------

Když je IsObjectIcon == false, tato hodnota se ignoruje. Řetězec může být zkrácen podle velikosti ikony Ole.

**Vrací:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Vrací nebo nastavuje titulek pro ikonu OleObject. Čtení/Zápis String.

--------------------

Když je IsObjectIcon == false, tato hodnota se ignoruje. Řetězec může být zkrácen podle velikosti ikony Ole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Vrací nebo nastavuje název objektu. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Vrací nebo nastavuje název objektu. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Vrací ProgID objektu. Pouze pro čtení String.

**Vrací:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Vrací ProgID objektu. Pouze pro čtení String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Vrací úplnou cestu k propojenému souboru. Použije se krátký název souboru. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Vrací úplnou cestu k propojenému souboru. Použije se dlouhý název souboru. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Vrací úplnou cestu k propojenému souboru. Použije se dlouhý název souboru. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Vrací relativní cestu k propojenému souboru, pokud je přítomna, jinak vrací prázdný řetězec. Pouze pro čtení String.

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

V prezentacích Ppt mohou některé odkazy OLE objektů mít relativní reprezentaci.

**Vrací:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

Vrací název souboru vloženého OLE objektu

**Vrací:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Vrací cestu vloženého OLE objektu

**Vrací:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Získává nebo nastavuje informace o vložených OLE datech. Čtení/Zápis [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Vrací:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Nastavuje informace o vložených OLE datech.

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Vložená data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Tato metoda mění vlastnosti objektu tak, aby odrážely nová data, a nastavuje příznak IsObjectLink na false, což značí, že OLE objekt je vložen. |
### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Určuje, zda je objekt viditelný jako ikona. Čtení/Zápis boolean .

**Vrací:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Určuje, zda je objekt viditelný jako ikona. Čtení/Zápis boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Určuje, zda je objekt propojen s externím souborem. Pouze pro čtení boolean .

**Vrací:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Určuje, zda je propojený vložený objekt automaticky aktualizován při otevření nebo tisku prezentace. Čtení/Zápis boolean .

**Vrací:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Určuje, zda je propojený vložený objekt automaticky aktualizován při otevření nebo tisku prezentace. Čtení/Zápis boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
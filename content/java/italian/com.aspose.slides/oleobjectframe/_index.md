---
title: OleObjectFrame
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta un oggetto OLE su una diapositiva.
type: docs
url: /it/com.aspose.slides/oleobjectframe/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Rappresenta un oggetto OLE su una diapositiva.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Carica il file PPTX in un oggetto presentation
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Accede alla prima diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Converte la forma in OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Legge l'oggetto OLE e lo scrive su disco
>      if (oleObjectFrame != null) {
>          // Ottiene i dati del file incorporato
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Ottiene l'estensione del file incorporato
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Crea un percorso per salvare il file estratto
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Salva i dati estratti
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Restituisce l'oggetto delle proprietà di riempimento immagine OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Restituisce o imposta il titolo per l'icona OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Restituisce o imposta il titolo per l'icona OleObject. |
| [getObjectName()](#getObjectName--) | Restituisce o imposta il nome di un oggetto. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Restituisce o imposta il nome di un oggetto. |
| [getObjectProgId()](#getObjectProgId--) | Restituisce il ProgID di un oggetto. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Restituisce il ProgID di un oggetto. |
| [getLinkFileName()](#getLinkFileName--) | Restituisce il percorso completo a un file collegato. |
| [getLinkPathLong()](#getLinkPathLong--) | Restituisce il percorso completo a un file collegato. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Restituisce il percorso completo a un file collegato. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Restituisce il percorso relativo a un file collegato se presente, altrimenti restituisce una stringa vuota. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Restituisce il nome file dell'oggetto OLE incorporato |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Restituisce il percorso dell'oggetto OLE incorporato |
| [getEmbeddedData()](#getEmbeddedData--) | Restituisce o imposta informazioni sui dati OLE incorporati. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Imposta informazioni sui dati OLE incorporati. |
| [isObjectIcon()](#isObjectIcon--) | Determina se un oggetto è visibile come icona. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Determina se un oggetto è visibile come icona. |
| [isObjectLink()](#isObjectLink--) | Determina se un oggetto è collegato a un file esterno. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Determina se l'oggetto OLE collegato è aggiornato automaticamente quando la presentazione viene aperta o stampata. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Determina se l'oggetto OLE collegato è aggiornato automaticamente quando la presentazione viene aperta o stampata. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


Restituisce l'oggetto delle proprietà di riempimento immagine OleObject. Solo lettura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Restituisce:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```


Restituisce o imposta il titolo per l'icona OleObject. Lettura/Scrittura String.

--------------------

Quando IsObjectIcon == false questo valore è ignorato. La stringa può essere troncata in base alle dimensioni dell'icona Ole.

**Restituisce:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```


Restituisce o imposta il titolo per l'icona OleObject. Lettura/Scrittura String.

--------------------

Quando IsObjectIcon == false questo valore è ignorato. La stringa può essere troncata in base alle dimensioni dell'icona Ole.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```


Restituisce o imposta il nome di un oggetto. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```


Restituisce o imposta il nome di un oggetto. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```


Restituisce il ProgID di un oggetto. Solo lettura String.

**Restituisce:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```


Restituisce il ProgID di un oggetto. Solo lettura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```


Restituisce il percorso completo a un file collegato. Verrà usato il nome file breve. Solo lettura String.

**Restituisce:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Restituisce il percorso completo a un file collegato. Verrà usato il nome file lungo. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Restituisce il percorso completo a un file collegato. Verrà usato il nome file lungo. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```


Restituisce il percorso relativo a un file collegato se presente, altrimenti restituisce una stringa vuota. Solo lettura String.

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

Nelle presentazioni Ppt, alcuni collegamenti di oggetti Ole possono avere una rappresentazione relativa.

**Restituisce:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```


Restituisce il nome file dell'oggetto OLE incorporato

**Restituisce:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```


Restituisce il percorso dell'oggetto OLE incorporato

**Restituisce:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```


Restituisce o imposta informazioni sui dati OLE incorporati. Lettura/Scrittura [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Restituisce:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


Imposta informazioni sui dati OLE incorporati.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Dati incorporati [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

Questo metodo modifica le proprietà dell'oggetto per riflettere i nuovi dati e imposta il flag IsObjectLink a false, indicando che l'oggetto OLE è incorporato. |
### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```


Determina se un oggetto è visibile come icona. Lettura/Scrittura boolean .

**Restituisce:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```


Determina se un oggetto è visibile come icona. Lettura/Scrittura boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```


Determina se un oggetto è collegato a un file esterno. Solo lettura boolean .

**Restituisce:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```


Determina se l'oggetto OLE collegato è aggiornato automaticamente quando la presentazione viene aperta o stampata. Lettura/Scrittura boolean .

**Restituisce:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```


Determina se l'oggetto OLE collegato è aggiornato automaticamente quando la presentazione viene aperta o stampata. Lettura/Scrittura boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
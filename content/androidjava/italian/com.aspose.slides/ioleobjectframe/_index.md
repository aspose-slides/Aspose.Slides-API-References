---
title: IOleObjectFrame
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta un oggetto OLE su una diapositiva.
type: docs
url: /it/com.aspose.slides/ioleobjectframe/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Rappresenta un oggetto OLE su una diapositiva.
## Metodi

| Method | Description |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Restituisce l'oggetto delle proprietà di riempimento immagine OleObject. |
| [getObjectName()](#getObjectName--) | Restituisce o imposta il nome di un oggetto. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Restituisce o imposta il nome di un oggetto. |
| [getEmbeddedData()](#getEmbeddedData--) | Ottiene informazioni sui dati incorporati OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Imposta informazioni sui dati incorporati OLE. |
| [getObjectProgId()](#getObjectProgId--) | Restituisce il ProgID di un oggetto. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Restituisce il ProgID di un oggetto. |
| [getLinkFileName()](#getLinkFileName--) | Restituisce il percorso completo di un file collegato. |
| [getLinkPathLong()](#getLinkPathLong--) | Restituisce il percorso completo di un file collegato. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Restituisce il percorso completo di un file collegato. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Restituisce il percorso relativo di un file collegato se presente, altrimenti restituisce una stringa vuota. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Restituisce il nome file dell'oggetto OLE incorporato |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Restituisce il percorso dell'oggetto OLE incorporato |
| [isObjectIcon()](#isObjectIcon--) | Determina se un oggetto è visibile come icona. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Determina se un oggetto è visibile come icona. |
| [isObjectLink()](#isObjectLink--) | Determina se un oggetto è collegato a un file esterno. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Determina se l'oggetto incorporato collegato viene aggiornato automaticamente quando la presentazione viene aperta o stampata. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Determina se l'oggetto incorporato collegato viene aggiornato automaticamente quando la presentazione viene aperta o stampata. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Restituisce o imposta il titolo per l'icona OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Restituisce o imposta il titolo per l'icona OleObject. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Restituisce l'oggetto delle proprietà di riempimento immagine OleObject. Solo lettura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Restituisce:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```


Restituisce o imposta il nome di un oggetto. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


Restituisce o imposta il nome di un oggetto. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


Ottiene informazioni sui dati incorporati OLE. Solo lettura [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Restituisce:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


Imposta informazioni sui dati incorporati OLE.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Dati incorporati [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Questo metodo modifica le proprietà dell'oggetto per riflettere i nuovi dati e imposta il flag IsObjectLink a false, indicando che l'oggetto OLE è incorporato. |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```


Restituisce il ProgID di un oggetto. Solo lettura String.

**Restituisce:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```


Restituisce il ProgID di un oggetto. Solo lettura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


Restituisce il percorso completo di un file collegato. Verrà usato il nome file breve. Solo lettura String.

**Restituisce:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Restituisce il percorso completo di un file collegato. Verrà usato il nome file lungo. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Restituisce il percorso completo di un file collegato. Verrà usato il nome file lungo. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```


Restituisce il percorso relativo di un file collegato se presente, altrimenti restituisce una stringa vuota. Solo lettura String.

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
public abstract String getEmbeddedFileLabel()
```


Restituisce il nome file dell'oggetto OLE incorporato

**Restituisce:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```


Restituisce il percorso dell'oggetto OLE incorporato

**Restituisce:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```


Determina se un oggetto è visibile come icona. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```


Determina se un oggetto è visibile come icona. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```


Determina se un oggetto è collegato a un file esterno. Solo lettura boolean.

**Restituisce:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


Determina se l'oggetto incorporato collegato viene aggiornato automaticamente quando la presentazione viene aperta o stampata. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


Determina se l'oggetto incorporato collegato viene aggiornato automaticamente quando la presentazione viene aperta o stampata. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


Restituisce o imposta il titolo per l'icona OleObject. Lettura/scrittura String.

--------------------

Quando IsObjectIcon == false questo valore è ignorato. La stringa può essere troncata in base alle dimensioni dell'icona OLE.

**Restituisce:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


Restituisce o imposta il titolo per l'icona OleObject. Lettura/scrittura String.

--------------------

Quando IsObjectIcon == false questo valore è ignorato. La stringa può essere troncata in base alle dimensioni dell'icona OLE.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
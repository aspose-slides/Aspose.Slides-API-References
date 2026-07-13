---
title: Control
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un controllo ActiveX.
type: docs
url: /it/com.aspose.slides/control/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Rappresenta un controllo ActiveX.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPersistence()](#getPersistence--) | Ottiene il metodo utilizzato per memorizzare le proprietà del controllo ActiveX. |
| [getName()](#getName--) | Ottiene o imposta il nome di questo controllo. |
| [setName(String value)](#setName-java.lang.String-) | Ottiene o imposta il nome di questo controllo. |
| [getClassId()](#getClassId--) | Ottiene l'ID della classe di questo controllo. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Ottiene l'ID della classe di questo controllo. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Restituisce l'oggetto delle proprietà di riempimento immagine del controllo. |
| [getFrame()](#getFrame--) | Restituisce o imposta il frame del controllo. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Restituisce o imposta il frame del controllo. |
| [getProperties()](#getProperties--) | Restituisce una collezione di proprietà ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Specifica la persistenza di un controllo ActiveX quando il metodo utilizzato per persistere è PersistStream, PersistStreamInit o PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Ottiene il metodo utilizzato per memorizzare le proprietà del controllo ActiveX. Sola lettura [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Usa il tuo metodo per gestire le proprietà ActiveX memorizzate nel suo file binario
>  }
> ```


**Restituisce:**
int
### getName() {#getName--}
```
public final String getName()
```

Ottiene o imposta il nome di questo controllo. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Ottiene o imposta il nome di questo controllo. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Ottiene l'ID della classe di questo controllo. Sola lettura java.util.UUID.

**Restituisce:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Ottiene l'ID della classe di questo controllo. Sola lettura java.util.UUID.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Restituisce l'oggetto delle proprietà di riempimento immagine del controllo. Sola lettura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Restituisce:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Restituisce o imposta il frame del controllo. Lettura/scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Restituisce:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Restituisce o imposta il frame del controllo. Lettura/scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Restituisce una collezione di proprietà ActiveX. Sola lettura [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Nota: Aspose.Slides supporta solo proprietà ActiveX basate su XML. Se le proprietà sono archiviate in formato binario, questa proprietà restituirà null.

**Restituisce:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Specifica la persistenza di un controllo ActiveX quando il metodo utilizzato per persistere è PersistStream, PersistStreamInit o PersistStorage.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Usa il tuo metodo per gestire le proprietà ActiveX archiviate nel suo file binario
>  }
> ```


**Restituisce:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva base. Sola lettura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione. Sola lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)
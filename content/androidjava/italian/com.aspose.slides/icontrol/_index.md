---
title: IControl
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un controllo ActiveX.
type: docs
url: /it/com.aspose.slides/icontrol/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Rappresenta un controllo ActiveX.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Restituisce il nome di questo controllo. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce il nome di questo controllo. |
| [getClassId()](#getClassId--) | Ottiene l'ID di classe di questo controllo. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Restituisce l'oggetto delle proprietà di riempimento immagine di ControlEx. |
| [getFrame()](#getFrame--) | Restituisce o imposta il frame del controllo. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Restituisce o imposta il frame del controllo. |
| [getProperties()](#getProperties--) | Restituisce una collezione di proprietà ActiveX. |
| [getPersistence()](#getPersistence--) | Ottiene il metodo usato per memorizzare le proprietà del controllo ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Specifica la persistenza di un controllo ActiveX quando il metodo usato per persistere è PersistStream, PersistStreamInit o PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

Restituisce il nome di questo controllo. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Restituisce il nome di questo controllo. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Ottiene l'ID di classe di questo controllo. Sola lettura java.util.UUID.

**Restituisce:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Restituisce l'oggetto delle proprietà di riempimento immagine di ControlEx. Sola lettura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Restituisce:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Restituisce o imposta il frame del controllo. Lettura/Scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Restituisce:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Restituisce o imposta il frame del controllo. Lettura/Scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Restituisce una collezione di proprietà ActiveX. Sola lettura [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Restituisce:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Ottiene il metodo usato per memorizzare le proprietà del controllo ActiveX. Sola lettura [PersistenceType](../../com.aspose.slides/persistencetype).

**Restituisce:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Specifica la persistenza di un controllo ActiveX quando il metodo usato per persistere è PersistStream, PersistStreamInit o PersistStorage.

**Restituisce:**
byte[]
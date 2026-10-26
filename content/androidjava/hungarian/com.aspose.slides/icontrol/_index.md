---
title: IControl
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Egy ActiveX vezérlőt képvisel.
type: docs
url: /hu/com.aspose.slides/icontrol/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Egy ActiveX vezérlőt képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getName()](#getName--) | Visszaadja ennek a vezérlőnek a nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja ennek a vezérlőnek a nevét. |
| [getClassId()](#getClassId--) | Lekéri ennek a vezérlőnek az osztályazonosítóját. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Visszaadja a ControlEx kép kitöltési tulajdonságok objektumát. |
| [getFrame()](#getFrame--) | Visszaadja vagy beállítja a vezérlő keretét. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Visszaadja vagy beállítja a vezérlő keretét. |
| [getProperties()](#getProperties--) | Visszaad egy gyűjteményt az ActiveX tulajdonságokról. |
| [getPersistence()](#getPersistence--) | Lekéri az ActiveX vezérlő tulajdonságainak tárolására használt módszert. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Megadja egy ActiveX vezérlő állandóságát, amikor a perzisztencia módszere a PersistStream, PersistStreamInit vagy PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

Visszaadja ennek a vezérlőnek a nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Visszaadja ennek a vezérlőnek a nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Lekéri ennek a vezérlőnek az osztályazonosítót. Csak olvasható java.util.UUID.

**Visszatér:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Visszaadja a ControlEx kép kitöltési tulajdonságok objektumát. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatér:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Visszaadja vagy beállítja a vezérlő keretét. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Visszatér:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Visszaadja vagy beállítja a vezérlő keretét. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Visszaad egy gyűjteményt az ActiveX tulajdonságokról. Csak olvasható [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Visszatér:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Lekéri az ActiveX vezérlő tulajdonságainak tárolására használt módszert. Csak olvasható [PersistenceType](../../com.aspose.slides/persistencetype).

**Visszatér:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Megadja egy ActiveX vezérlő állandóságát, amikor a perzisztencia módszere a PersistStream, PersistStreamInit vagy PersistStorage.

**Visszatér:**
byte[]
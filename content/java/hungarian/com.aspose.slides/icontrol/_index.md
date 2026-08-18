---
title: IControl
second_title: Aspose.Slides for Java API-referencia
description: Egy ActiveX vezérlőt ábrázol.
type: docs
url: /hu/com.aspose.slides/icontrol/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Az ActiveX vezérlőt ábrázolja.

## Módszerek

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Visszaadja a vezérlő nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja a vezérlő nevét. |
| [getClassId()](#getClassId--) | A vezérlő osztályazonosítóját adja vissza. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Visszaadja a ControlEx képtöltési tulajdonság objektumot. |
| [getFrame()](#getFrame--) | Visszaadja vagy beállítja a vezérlő keretét. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Visszaadja vagy beállítja a vezérlő keretét. |
| [getProperties()](#getProperties--) | Visszaad egy gyűjteményt az ActiveX tulajdonságokról. |
| [getPersistence()](#getPersistence--) | Azt a módszert adja vissza, amelyet az ActiveX vezérlő tulajdonságainak tárolásához használnak. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Megadja egy ActiveX vezérlő állapotmentését, amikor a mentéshez használt módszer a PersistStream, PersistStreamInit vagy PersistStorage. |

### getName() {#getName--}
```
public abstract String getName()
```

Visszaadja a vezérlő nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Visszaadja a vezérlő nevét. Olvasás/írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

A vezérlő osztályazonosítóját adja vissza. Csak olvasható java.util.UUID.

**Visszatér:**
java.util.UUID

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Visszaadja a ControlEx képtöltési tulajdonság objektumot. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

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
| Parameter | Type | Description |
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

Azt a módszert adja vissza, amelyet az ActiveX vezérlő tulajdonságainak tárolásához használnak. Csak olvasható [PersistenceType](../../com.aspose.slides/persistencetype).

**Visszatér:**
int

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Megadja egy ActiveX vezérlő állapotmentését, amikor a mentéshez használt módszer a PersistStream, PersistStreamInit vagy PersistStorage.

**Visszatér:**
byte[]
---
title: IControl
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en ActiveX-kontroll.
type: docs
url: /sv/com.aspose.slides/icontrol/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Representerar en ActiveX-kontroll.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Returnerar namnet på den här kontrollen. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar namnet på den här kontrollen. |
| [getClassId()](#getClassId--) | Hämtar klass-id för den här kontrollen. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returnerar ControlEx bildfyllnings-egenskapsobjekt. |
| [getFrame()](#getFrame--) | Returnerar eller anger kontrollens ram. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returnerar eller anger kontrollens ram. |
| [getProperties()](#getProperties--) | Returnerar en samling av ActiveX-egenskaper. |
| [getPersistence()](#getPersistence--) | Hämtar metoden som används för att lagra egenskaper för ActiveX-kontrollen. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Anger beständigheten för en ActiveX-kontroll när den metod som används för att bestå är antingen PersistStream, PersistStreamInit eller PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

Returnerar namnet på den här kontrollen. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Returnerar namnet på den här kontrollen. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Hämtar klass-id för den här kontrollen. Endast läsning java.util.UUID.

**Returnerar:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Returnerar ControlEx bildfyllnings-egenskapsobjekt. Endast läsning [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returnerar:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Returnerar eller anger kontrollens ram. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Returnerar:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Returnerar eller anger kontrollens ram. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Returnerar en samling av ActiveX-egenskaper. Endast läsning [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Returnerar:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Hämtar metoden som används för att lagra egenskaper för ActiveX-kontrollen. Endast läsning [PersistenceType](../../com.aspose.slides/persistencetype).

**Returnerar:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Anger beständigheten för en ActiveX-kontroll när den metod som används för att bestå är antingen PersistStream, PersistStreamInit eller PersistStorage.

**Returnerar:**
byte[]
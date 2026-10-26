---
title: IControl
second_title: Aspose.Slides för Java API-referens
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
| [getName()](#getName--) | Returnerar namn på kontrollen. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar namn på kontrollen. |
| [getClassId()](#getClassId--) | Hämtar klass-id för kontrollen. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returnerar ControlEx image fill properties-objekt. |
| [getFrame()](#getFrame--) | Returnerar eller anger kontrollens ram. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returnerar eller anger kontrollens ram. |
| [getProperties()](#getProperties--) | Returnerar en samling av ActiveX-egenskaper. |
| [getPersistence()](#getPersistence--) | Hämtar metoden som används för att lagra egenskaper för ActiveX-kontrollen. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Anger beständigheten för en ActiveX-kontroll när den metod som används för beständighet är antingen PersistStream, PersistStreamInit eller PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

Returnerar namn på kontrollen. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Returnerar namn på kontrollen. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Hämtar klass-id för kontrollen. Skrivskyddad java.util.UUID.

**Returnerar:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Returnerar ControlEx image fill properties-objekt. Skrivskyddad [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

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

Returnerar en samling av ActiveX-egenskaper. Skrivskyddad [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Returnerar:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Hämtar metoden som används för att lagra egenskaper för ActiveX-kontrollen. Skrivskyddad [PersistenceType](../../com.aspose.slides/persistencetype).

**Returnerar:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Anger beständigheten för en ActiveX-kontroll när den metod som används för beständighet är antingen PersistStream, PersistStreamInit eller PersistStorage.

**Returnerar:**
byte[]
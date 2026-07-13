---
title: IControl
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een ActiveX-controle voor.
type: docs
url: /nl/com.aspose.slides/icontrol/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Stelt een ActiveX-controle voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Retourneert de naam van deze controle. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert de naam van deze controle. |
| [getClassId()](#getClassId--) | Haalt de class-id van deze controle op. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Retourneert ControlEx image fill properties object. |
| [getFrame()](#getFrame--) | Retourneert of stelt het frame van de controle in. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Retourneert of stelt het frame van de controle in. |
| [getProperties()](#getProperties--) | Retourneert een collectie van ActiveX-eigenschappen. |
| [getPersistence()](#getPersistence--) | Haalt de methode op die wordt gebruikt om eigenschappen van de ActiveX-controle op te slaan. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Specificeert de persistentie van een ActiveX-controle wanneer de gebruikte persisteringsmethode PersistStream, PersistStreamInit of PersistStorage is. |
### getName() {#getName--}
```
public abstract String getName()
```

Retourneert de naam van deze controle. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Retourneert de naam van deze controle. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Haalt de class-id van deze controle op. Alleen-lezen java.util.UUID.

**Retourneert:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Retourneert ControlEx image fill properties object. Alleen-lezen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retourneert:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Retourneert of stelt het frame van de controle in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Retourneert:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Retourneert of stelt het frame van de controle in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Retourneert een collectie van ActiveX-eigenschappen. Alleen-lezen [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Retourneert:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Haalt de methode op die wordt gebruikt om eigenschappen van de ActiveX-controle op te slaan. Alleen-lezen [PersistenceType](../../com.aspose.slides/persistencetype).

**Retourneert:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Specificeert de persistentie van een ActiveX-controle wanneer de gebruikte persisteringsmethode PersistStream, PersistStreamInit of PersistStorage is.

**Retourneert:**
byte[]
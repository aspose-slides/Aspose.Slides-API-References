---
title: Control
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een ActiveX-besturingselement.
type: docs
url: /nl/com.aspose.slides/control/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Stelt een ActiveX-besturingselement voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPersistence()](#getPersistence--) | Haalt de methode op die wordt gebruikt om eigenschappen van het ActiveX-besturingselement op te slaan. |
| [getName()](#getName--) | Haalt de naam van dit besturingselement op of stelt deze in. |
| [setName(String value)](#setName-java.lang.String-) | Haalt de naam van dit besturingselement op of stelt deze in. |
| [getClassId()](#getClassId--) | Haalt de klasse-ID van dit besturingselement op. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Haalt de klasse-ID van dit besturingselement op. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Retourneert het object met vul-eigenschappen van de besturingselementafbeelding. |
| [getFrame()](#getFrame--) | Retourneert of stelt het frame van het besturingselement in. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Retourneert of stelt het frame van het besturingselement in. |
| [getProperties()](#getProperties--) | Retourneert een verzameling ActiveX-eigenschappen. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Specificeert de persistentie van een ActiveX-besturingselement wanneer de gebruikte methode om te bewaren PersistStream, PersistStreamInit of PersistStorage is. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```


Haalt de methode op die wordt gebruikt om eigenschappen van het ActiveX-besturingselement op te slaan. Alleen-lezen [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //Gebruik uw eigen methode om ActiveX-eigenschappen die in het binaire bestand zijn opgeslagen te beheren
>  }
> ```


**Retour:**
int
### getName() {#getName--}
```
public final String getName()
```


Haalt de naam van dit besturingselement op of stelt deze in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Haalt de naam van dit besturingselement op of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public final UUID getClassId()
```


Haalt de klasse-ID van dit besturingselement op. Alleen-lezen java.util.UUID.

**Retour:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```


Haalt de klasse-ID van dit besturingselement op. Alleen-lezen java.util.UUID.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.UUID |  |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


Retourneert het object met vul-eigenschappen van de besturingselementafbeelding. Alleen-lezen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retour:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```


Retourneert of stelt het frame van het besturingselement in. Lezen/Schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Retour:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```


Retourneert of stelt het frame van het besturingselement in. Lezen/Schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```


Retourneert een verzameling ActiveX-eigenschappen. Alleen-lezen [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Opmerking: Aspose.Slides ondersteunt alleen op XML gebaseerde ActiveX-eigenschappen. Als eigenschappen in binair formaat zijn opgeslagen, zal deze eigenschap null retourneren.

**Retour:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```


Specificeert de persistentie van een ActiveX-besturingselement wanneer de gebruikte methode om te bewaren PersistStream, PersistStreamInit of PersistStorage is.

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
>      YourMethodHere(control.getActiveXControlBinary()); //Gebruik uw eigen methode om ActiveX-eigenschappen die in het binaire bestand zijn opgeslagen te beheren
>  }
> ```


**Retour:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Retourneert de basis-slide. Alleen-lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retour:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Retourneert de presentatie. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation)
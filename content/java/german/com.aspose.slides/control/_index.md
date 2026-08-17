---
title: Control
second_title: Aspose.Slides für Java API Referenz
description: Stellt ein ActiveX-Steuerelement dar.
type: docs
url: /de/com.aspose.slides/control/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Stellt ein ActiveX-Steuerelement dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPersistence()](#getPersistence--) | Ermittelt die Methode, die zum Speichern von Eigenschaften des ActiveX-Steuerelements verwendet wird. |
| [getName()](#getName--) | Ermittelt oder legt den Namen dieses Steuerelements fest. |
| [setName(String value)](#setName-java.lang.String-) | Ermittelt oder legt den Namen dieses Steuerelements fest. |
| [getClassId()](#getClassId--) | Ermittelt die Klassen-ID dieses Steuerelements. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Ermittelt die Klassen-ID dieses Steuerelements. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Gibt das Objekt für die Bildfüllung des Steuerelements zurück. |
| [getFrame()](#getFrame--) | Gibt den Rahmen des Steuerelements zurück oder legt ihn fest. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Gibt den Rahmen des Steuerelements zurück oder legt ihn fest. |
| [getProperties()](#getProperties--) | Gibt eine Sammlung von ActiveX-Eigenschaften zurück. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Gibt die Persistenz eines ActiveX-Steuerelements an, wenn die zum Persistieren verwendete Methode entweder PersistStream, PersistStreamInit oder PersistStorage ist. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Ermittelt die Methode, die zum Speichern von Eigenschaften des ActiveX-Steuerelements verwendet wird. Nur lesbar [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //Verwenden Sie Ihre eigene Methode zur Verwaltung von ActiveX-Eigenschaften, die in deren Binärdatei gespeichert sind
>  }
> ```


**Rückgabe:**
int
### getName() {#getName--}
```
public final String getName()
```

Ermittelt oder legt den Namen dieses Steuerelements fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Ermittelt oder legt den Namen dieses Steuerelements fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Ermittelt die Klassen-ID dieses Steuerelements. Nur lesbar java.util.UUID.

**Rückgabe:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Ermittelt die Klassen-ID dieses Steuerelements. Nur lesbar java.util.UUID.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID |  |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Gibt das Objekt für die Bildfüllung des Steuerelements zurück. Nur lesbar [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Rückgabe:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Gibt den Rahmen des Steuerelements zurück oder legt ihn fest. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Rückgabe:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Gibt den Rahmen des Steuerelements zurück oder legt ihn fest. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Gibt eine Sammlung von ActiveX-Eigenschaften zurück. Nur lesbar [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Hinweis: Aspose.Slides unterstützt nur XML-basierte ActiveX-Eigenschaften. Wenn Eigenschaften im Binärformat gespeichert sind, gibt diese Eigenschaft null zurück.

**Rückgabe:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Gibt die Persistenz eines ActiveX-Steuerelements an, wenn die zum Persistieren verwendete Methode entweder PersistStream, PersistStreamInit oder PersistStorage ist.

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
>      YourMethodHere(control.getActiveXControlBinary()); //Verwenden Sie Ihre eigene Methode zur Verwaltung von ActiveX-Eigenschaften, die in deren Binärdatei gespeichert sind
>  }
> ```


**Rückgabe:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die Basisfolie zurück. Nur lesbar [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die Präsentation zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)
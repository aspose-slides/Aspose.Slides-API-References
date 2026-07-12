---
title: Control
second_title: Aspose.Slides für Android über die Java API Referenz
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
| [getPersistence()](#getPersistence--) | Ruft die Methode ab, die zum Speichern von Eigenschaften des ActiveX-Steuerelements verwendet wird. |
| [getName()](#getName--) | Ruft den Namen dieses Steuerelements ab oder setzt ihn. |
| [setName(String value)](#setName-java.lang.String-) | Ruft den Namen dieses Steuerelements ab oder setzt ihn. |
| [getClassId()](#getClassId--) | Ruft die Klassen-ID dieses Steuerelements ab. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Ruft die Klassen-ID dieses Steuerelements ab. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Gibt das Objekt für die Bildfüllung des Steuerelements zurück. |
| [getFrame()](#getFrame--) | Gibt den Rahmen des Steuerelements zurück oder setzt ihn. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Gibt den Rahmen des Steuerelements zurück oder setzt ihn. |
| [getProperties()](#getProperties--) | Gibt eine Sammlung von ActiveX-Eigenschaften zurück. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Gibt die Persistenz eines ActiveX-Steuerelements an, wenn die zum Persistieren verwendete Methode entweder PersistStream, PersistStreamInit oder PersistStorage ist. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```


Ruft die Methode ab, die zum Speichern von Eigenschaften des ActiveX-Steuerelements verwendet wird. Nur lesen [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //Verwenden Sie Ihre eigene Methode zum Verwalten von ActiveX-Eigenschaften, die in ihrer Binärdatei gespeichert sind
>  }
> ```

**Rückgabewert:**
int
### getName() {#getName--}
```
public final String getName()
```


Ruft den Namen dieses Steuerelements ab oder setzt ihn. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ruft den Namen dieses Steuerelements ab oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```


Ruft die Klassen-ID dieses Steuerelements ab. Nur lesbar java.util.UUID.

**Rückgabewert:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```


Ruft die Klassen-ID dieses Steuerelements ab. Nur lesbar java.util.UUID.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


Gibt das Objekt für die Bildfüllung des Steuerelements zurück. Nur lesen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Rückgabewert:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```


Gibt den Rahmen des Steuerelements zurück oder setzt ihn. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Rückgabewert:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```


Gibt den Rahmen des Steuerelements zurück oder setzt ihn. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

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

Hinweis: Aspose.Slides unterstützt nur XML-basierte ActiveX-Eigenschaften. Wenn Eigenschaften im Binärformat gespeichert werden, gibt diese Eigenschaft null zurück.

**Rückgabewert:**
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
>      YourMethodHere(control.getActiveXControlBinary()); //Verwenden Sie Ihre eigene Methode zum Verwalten von ActiveX-Eigenschaften, die in ihrer Binärdatei gespeichert sind
>  }
> ```


**Rückgabewert:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Gibt die Basisfolie zurück. Nur lesbar [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabewert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Gibt die Präsentation zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**
[IPresentation](../../com.aspose.slides/ipresentation)
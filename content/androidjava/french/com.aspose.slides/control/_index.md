---
title: Control
second_title: Aspose.Slides pour Android via la référence d'API Java
description: Représente un contrôle ActiveX.
type: docs
url: /fr/com.aspose.slides/control/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Représente un contrôle ActiveX.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPersistence()](#getPersistence--) | Obtient la méthode utilisée pour stocker les propriétés du contrôle ActiveX. |
| [getName()](#getName--) | Obtient ou définit le nom de ce contrôle. |
| [setName(String value)](#setName-java.lang.String-) | Obtient ou définit le nom de ce contrôle. |
| [getClassId()](#getClassId--) | Obtient l'identifiant de classe de ce contrôle. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Obtient l'identifiant de classe de ce contrôle. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Renvoie l'objet des propriétés de remplissage d'image du contrôle. |
| [getFrame()](#getFrame--) | Renvoie ou définit le cadre du contrôle. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Renvoie ou définit le cadre du contrôle. |
| [getProperties()](#getProperties--) | Renvoie une collection de propriétés ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Spécifie la persistance d'un contrôle ActiveX lorsque la méthode utilisée pour persister est soit PersistStream, PersistStreamInit ou PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Obtient la méthode utilisée pour stocker les propriétés du contrôle ActiveX. Lecture seule [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //Utilisez votre propre méthode pour gérer les propriétés ActiveX stockées dans son fichier binaire
>  }
>  ```

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```

Gets or sets the name of this control. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Gets or sets the name of this control. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Gets class id of this control. Read-only java.util.UUID.

**Returns:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Gets class id of this control. Read-only java.util.UUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Returns Control image fill properties object. Read-only [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Returns or sets control's frame. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Returns or sets control's frame. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Renvoie une collection de propriétés ActiveX. Lecture seule [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Remarque : Aspose.Slides ne prend en charge que les propriétés ActiveX basées sur XML. Si les propriétés sont stockées au format binaire, cette propriété renverra null.

**Returns:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```
Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage.

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
>      YourMethodHere(control.getActiveXControlBinary()); //Utilisez votre propre méthode pour gérer les propriétés ActiveX stockées dans son fichier binaire
>  }
> ```

**Returns:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the base slide. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
Returns the presentation. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
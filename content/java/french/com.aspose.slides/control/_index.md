---
title: Control
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Renvoie l'objet de propriétés de remplissage d'image du contrôle. |
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
>      YourMethodHere(control.getActiveXControlBinary()); //Use your own method for managing ActiveX properties stored in its binary file
>  }
> ```

**Retour :**
int
### getName() {#getName--}
```
public final String getName()
```


Obtient ou définit le nom de ce contrôle. Lecture/écriture String.

**Retour :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Obtient ou définit le nom de ce contrôle. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```


Obtient l'identifiant de classe de ce contrôle. Lecture seule java.util.UUID.

**Retour :**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```


Obtient l'identifiant de classe de ce contrôle. Lecture seule java.util.UUID.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


Renvoie l'objet de propriétés de remplissage d'image du contrôle. Lecture seule [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retour :**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```


Renvoie ou définit le cadre du contrôle. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Retour :**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```


Renvoie ou définit le cadre du contrôle. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```


Renvoie une collection de propriétés ActiveX. Lecture seule [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Remarque : Aspose.Slides prend en charge uniquement les propriétés ActiveX basées sur XML. Si les propriétés sont stockées au format binaire, cette propriété renverra null.

**Retour :**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```


Spécifie la persistance d'un contrôle ActiveX lorsque la méthode utilisée pour persister est soit PersistStream, PersistStreamInit ou PersistStorage.

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

**Retour :**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Renvoie la diapositive de base. Lecture seule [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retour :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Renvoie la présentation. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation)
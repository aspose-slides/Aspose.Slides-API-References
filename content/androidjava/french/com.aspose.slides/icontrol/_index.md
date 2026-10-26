---
title: IControl
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un contrôle ActiveX.
type: docs
url: /fr/com.aspose.slides/icontrol/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Représente un contrôle ActiveX.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Renvoie le nom de ce contrôle. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie le nom de ce contrôle. |
| [getClassId()](#getClassId--) | Obtient l'identifiant de classe de ce contrôle. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Renvoie l'objet de propriétés de remplissage d'image ControlEx. |
| [getFrame()](#getFrame--) | Renvoie ou définit le cadre du contrôle. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Renvoie ou définit le cadre du contrôle. |
| [getProperties()](#getProperties--) | Renvoie une collection de propriétés ActiveX. |
| [getPersistence()](#getPersistence--) | Obtient la méthode utilisée pour stocker les propriétés du contrôle ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Spécifie la persistance d'un contrôle ActiveX lorsque la méthode utilisée pour persister est soit PersistStream, PersistStreamInit ou PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```


Renvoie le nom de ce contrôle. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Renvoie le nom de ce contrôle. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```


Obtient l'identifiant de classe de ce contrôle. Lecture seule java.util.UUID.

**Renvoie :**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Renvoie l'objet de propriétés de remplissage d'image ControlEx. Lecture seule [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Renvoie :**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


Renvoie ou définit le cadre du contrôle. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Renvoie :**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```


Renvoie ou définit le cadre du contrôle. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```


Renvoie une collection de propriétés ActiveX. Lecture seule [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Renvoie :**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```


Obtient la méthode utilisée pour stocker les propriétés du contrôle ActiveX. Lecture seule [PersistenceType](../../com.aspose.slides/persistencetype).

**Renvoie :**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```


Spécifie la persistance d'un contrôle ActiveX lorsque la méthode utilisée pour persister est soit PersistStream, PersistStreamInit ou PersistStorage.

**Renvoie :**
byte[]
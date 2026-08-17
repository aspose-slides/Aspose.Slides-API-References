---
title: IControl
second_title: Aspose.Slides für die Java API Referenz
description: Stellt ein ActiveX-Steuerelement dar.
type: docs
url: /de/com.aspose.slides/icontrol/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Represents an ActiveX control.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Gibt den Namen dieses Steuerelements zurück. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen dieses Steuerelements zurück. |
| [getClassId()](#getClassId--) | Ermittelt die Klassen-ID dieses Steuerelements. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Gibt das ControlEx-Bildfüllungs-Eigenschaftsobjekt zurück. |
| [getFrame()](#getFrame--) | Gibt den Rahmen des Steuerelements zurück oder setzt ihn. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Gibt den Rahmen des Steuerelements zurück oder setzt ihn. |
| [getProperties()](#getProperties--) | Gibt eine Sammlung von ActiveX-Eigenschaften zurück. |
| [getPersistence()](#getPersistence--) | Ermittelt die Methode, die zum Speichern der Eigenschaften des ActiveX-Steuerelements verwendet wird. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Gibt die Persistenz eines ActiveX-Steuerelements an, wenn die zum Persistieren verwendete Methode entweder PersistStream, PersistStreamInit oder PersistStorage ist. |

### getName() {#getName--}
```
public abstract String getName()
```

Gibt den Namen dieses Steuerelements zurück. Lese/Schreib String.

**Rückgabe:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Gibt den Namen dieses Steuerelements zurück. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Ermittelt die Klassen-ID dieses Steuerelements. Nur lesbar java.util.UUID.

**Rückgabe:**
java.util.UUID

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Gibt das ControlEx-Bildfüllungs-Eigenschaftsobjekt zurück. Nur lesbar [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Rückgabe:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Gibt den Rahmen des Steuerelements zurück oder setzt ihn. Lese/Schreib [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Rückgabe:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Gibt den Rahmen des Steuerelements zurück oder setzt ihn. Lese/Schreib [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Gibt eine Sammlung von ActiveX-Eigenschaften zurück. Nur lesbar [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Rückgabe:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Ermittelt die Methode, die zum Speichern der Eigenschaften des ActiveX-Steuerelements verwendet wird. Nur lesbar [PersistenceType](../../com.aspose.slides/persistencetype).

**Rückgabe:**
int

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Gibt die Persistenz eines ActiveX-Steuerelements an, wenn die zum Persistieren verwendete Methode entweder PersistStream, PersistStreamInit oder PersistStorage ist.

**Rückgabe:**
byte[]
---
title: IControl
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Reprezentuje kontrolkę ActiveX.
type: docs
url: /pl/com.aspose.slides/icontrol/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Reprezentuje kontrolkę ActiveX.
## Metody

| Metoda | Opis |
| --- | --- |
| [getName()](#getName--) | Zwraca nazwę tej kontrolki. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca nazwę tej kontrolki. |
| [getClassId()](#getClassId--) | Pobiera identyfikator klasy tej kontrolki. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Zwraca obiekt właściwości wypełnienia obrazu ControlEx. |
| [getFrame()](#getFrame--) | Zwraca lub ustawia ramkę kontrolki. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Zwraca lub ustawia ramkę kontrolki. |
| [getProperties()](#getProperties--) | Zwraca kolekcję właściwości ActiveX. |
| [getPersistence()](#getPersistence--) | Pobiera metodę używaną do przechowywania właściwości kontrolki ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Określa trwałość kontrolki ActiveX, gdy metodą utrwalania jest PersistStream, PersistStreamInit lub PersistStorage. |

### getName() {#getName--}
```
public abstract String getName()
```

Zwraca nazwę tej kontrolki. Odczyt/zapis String.

**Zwraca:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Zwraca nazwę tej kontrolki. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Pobiera identyfikator klasy tej kontrolki. Tylko do odczytu java.util.UUID.

**Zwraca:**
java.util.UUID

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Zwraca obiekt właściwości wypełnienia obrazu ControlEx. Tylko do odczytu [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Zwraca:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Zwraca lub ustawia ramkę kontrolki. Odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Zwraca:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Zwraca lub ustawia ramkę kontrolki. Odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Zwraca kolekcję właściwości ActiveX. Tylko do odczytu [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Zwraca:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Pobiera metodę używaną do przechowywania właściwości kontrolki ActiveX. Tylko do odczytu [PersistenceType](../../com.aspose.slides/persistencetype).

**Zwraca:**
int

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Określa trwałość kontrolki ActiveX, gdy metodą utrwalania jest PersistStream, PersistStreamInit lub PersistStorage.

**Zwraca:**
byte[]
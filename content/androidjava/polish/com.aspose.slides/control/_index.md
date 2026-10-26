---
title: Control
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Reprezentuje kontrolkę ActiveX.
type: docs
url: /pl/com.aspose.slides/control/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Reprezentuje kontrolkę ActiveX.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPersistence()](#getPersistence--) | Pobiera metodę używaną do przechowywania właściwości kontrolki ActiveX. |
| [getName()](#getName--) | Pobiera lub ustawia nazwę tej kontrolki. |
| [setName(String value)](#setName-java.lang.String-) | Pobiera lub ustawia nazwę tej kontrolki. |
| [getClassId()](#getClassId--) | Pobiera identyfikator klasy tej kontrolki. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Pobiera identyfikator klasy tej kontrolki. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Zwraca obiekt właściwości wypełnienia obrazu kontrolki. |
| [getFrame()](#getFrame--) | Pobiera lub ustawia ramkę kontrolki. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Pobiera lub ustawia ramkę kontrolki. |
| [getProperties()](#getProperties--) | Zwraca kolekcję właściwości ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Określa trwałość kontrolki ActiveX, gdy metodą utrwalania jest PersistStream, PersistStreamInit lub PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Pobiera metodę używaną do przechowywania właściwości kontrolki ActiveX. Tylko do odczytu [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //Użyj własnej metody do zarządzania właściwościami ActiveX przechowywanymi w jego pliku binarnym
>  }
> ```


**Zwraca:**
int

### getName() {#getName--}
```
public final String getName()
```

Pobiera lub ustawia nazwę tej kontrolki. String do odczytu i zapisu.

**Zwraca:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Pobiera lub ustawia nazwę tej kontrolki. String do odczytu i zapisu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Pobiera identyfikator klasy tej kontrolki. java.util.UUID tylko do odczytu.

**Zwraca:**
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Pobiera identyfikator klasy tej kontrolki. java.util.UUID tylko do odczytu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Zwraca obiekt właściwości wypełnienia obrazu kontrolki. [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat) tylko do odczytu.

**Zwraca:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Pobiera lub ustawia ramkę kontrolki. [IShapeFrame](../../com.aspose.slides/ishapeframe) do odczytu i zapisu.

**Zwraca:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Pobiera lub ustawia ramkę kontrolki. [IShapeFrame](../../com.aspose.slides/ishapeframe) do odczytu i zapisu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Zwraca kolekcję właściwości ActiveX. [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection) tylko do odczytu.

--------------------

Uwaga: Aspose.Slides obsługuje wyłącznie właściwości ActiveX oparte na XML. Jeśli właściwości są przechowywane w formacie binarnym, ta właściwość zwróci wartość null.

**Zwraca:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Określa trwałość kontrolki ActiveX, gdy metodą utrwalania jest PersistStream, PersistStreamInit lub PersistStorage.

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
>      YourMethodHere(control.getActiveXControlBinary()); //Użyj własnej metody do zarządzania właściwościami ActiveX przechowywanymi w jego pliku binarnym
>  }
> ```


**Zwraca:**
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca bazowy slajd. [IBaseSlide](../../com.aspose.slides/ibaseslide) tylko do odczytu.

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację. [IPresentation](../../com.aspose.slides/ipresentation) tylko do odczytu.

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)
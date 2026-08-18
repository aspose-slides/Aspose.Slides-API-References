---
title: Control
second_title: Aspose.Slides dla Java – odniesienie API
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
| [getFrame()](#getFrame--) | Zwraca lub ustawia ramkę kontrolki. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Zwraca lub ustawia ramkę kontrolki. |
| [getProperties()](#getProperties--) | Zwraca kolekcję właściwości ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Określa trwałość kontrolki ActiveX, gdy metodą persystencji jest PersistStream, PersistStreamInit lub PersistStorage. |
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
>      YourMethodHere(control.getActiveXControlBinary()); //Użyj własnej metody do zarządzania właściwościami ActiveX przechowywanymi w pliku binarnym
>  }
> ```

**Zwraca:**
int
### getName() {#getName--}
```
public final String getName()
```

Pobiera lub ustawia nazwę tej kontrolki. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Pobiera lub ustawia nazwę tej kontrolki. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Pobiera identyfikator klasy tej kontrolki. Tylko do odczytu java.util.UUID.

**Zwraca:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Pobiera identyfikator klasy tej kontrolki. Tylko do odczytu java.util.UUID.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Zwraca obiekt właściwości wypełnienia obrazu kontrolki. Tylko do odczytu [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Zwraca:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Zwraca lub ustawia ramkę kontrolki. Odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Zwraca:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Zwraca lub ustawia ramkę kontrolki. Odczyt/zapis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Zwraca kolekcję właściwości ActiveX. Tylko do odczytu [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Uwaga: Aspose.Slides obsługuje wyłącznie właściwości ActiveX oparte na XML. Jeśli właściwości są przechowywane w formacie binarnym, ta właściwość zwróci null.

**Zwraca:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Określa trwałość kontrolki ActiveX, gdy metodą persystencji jest PersistStream, PersistStreamInit lub PersistStorage.

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
>      YourMethodHere(control.getActiveXControlBinary()); //Użyj własnej metody do zarządzania właściwościami ActiveX przechowywanymi w pliku binarnym
>  }
> ```


**Zwraca:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca podstawowy slajd. Tylko do odczytu [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)
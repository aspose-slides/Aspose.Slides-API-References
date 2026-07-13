---
title: Control
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje ActiveX ovládací prvek.
type: docs
url: /cs/com.aspose.slides/control/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Representuje ActiveX ovládací prvek.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPersistence()](#getPersistence--) | Gets the method used to store properties of the ActiveX control. |
| [getName()](#getName--) | Gets or sets the name of this control. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the name of this control. |
| [getClassId()](#getClassId--) | Gets class id of this control. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Gets class id of this control. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returns Control image fill properties object. |
| [getFrame()](#getFrame--) | Returns or sets control's frame. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returns or sets control's frame. |
| [getProperties()](#getProperties--) | Returns a collection of ActiveX properties. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```


Gets the method used to store properties of the ActiveX control. Pouze ke čtení [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //Použijte vlastní metodu pro správu ActiveX vlastností uložených v jeho binárním souboru
>  }
> ```

**Vrací:**
int
### getName() {#getName--}
```
public final String getName()
```


Gets or sets the name of this control. Čtení/zápis String.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets the name of this control. Čtení/zápis String.

**Parametry:**
| Parameter | Type | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```


Gets class id of this control. Pouze ke čtení java.util.UUID.

**Vrací:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```


Gets class id of this control. Pouze ke čtení java.util.UUID.

**Parametry:**
| Parameter | Type | Popis |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


Returns Control image fill properties object. Pouze ke čtení [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Vrací:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```


Returns or sets control's frame. Čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Vrací:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```


Returns or sets control's frame. Čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametry:**
| Parameter | Type | Popis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```


Returns a collection of ActiveX properties. Pouze ke čtení [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Poznámka: Aspose.Slides supports only XML based ActiveX properties. If properties stored in binary format, this property will return null.

**Vrací:**
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
>      YourMethodHere(control.getActiveXControlBinary()); //Použijte vlastní metodu pro správu ActiveX vlastností uložených v jeho binárním souboru
>  }
> ```


**Vrací:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the base slide. Pouze ke čtení [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the presentation. Pouze ke čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
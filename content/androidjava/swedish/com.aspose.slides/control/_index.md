---
title: Control
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en ActiveX-kontroll.
type: docs
url: /sv/com.aspose.slides/control/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Representerar en ActiveX-kontroll.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPersistence()](#getPersistence--) | Hämtar metoden som används för att lagra egenskaper för ActiveX-kontrollen. |
| [getName()](#getName--) | Hämtar eller anger namnet på denna kontroll. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger namnet på denna kontroll. |
| [getClassId()](#getClassId--) | Hämtar klass-id för denna kontroll. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Hämtar klass-id för denna kontroll. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returnerar objekt för kontrollens bildfyllnings-egenskaper. |
| [getFrame()](#getFrame--) | Hämtar eller anger kontrollens ram. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Hämtar eller anger kontrollens ram. |
| [getProperties()](#getProperties--) | Returnerar en samling av ActiveX-egenskaper. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Anger beständigheten för en ActiveX-kontroll när den metod som används för beständighet är antingen PersistStream, PersistStreamInit eller PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Hämtar metoden som används för att lagra egenskaper för ActiveX-kontrollen. Skrivskyddad [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //Använd din egen metod för att hantera ActiveX-egenskaper som lagras i dess binära fil
>  }
> ```

**Returnerar:**
int
### getName() {#getName--}
```
public final String getName()
```

Hämtar eller anger namnet på denna kontroll. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Hämtar eller anger namnet på denna kontroll. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Hämtar klass-id för denna kontroll. Skrivskyddad java.util.UUID.

**Returnerar:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Hämtar klass-id för denna kontroll. Skrivskyddad java.util.UUID.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Returnerar objekt för kontrollens bildfyllnings-egenskaper. Skrivskyddad [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returnerar:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Hämtar eller anger kontrollens ram. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Returnerar:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Hämtar eller anger kontrollens ram. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Returnerar en samling av ActiveX-egenskaper. Skrivskyddad [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Obs: Aspose.Slides stöder endast XML-baserade ActiveX-egenskaper. Om egenskaper lagras i binärt format, returnerar denna egenskap null.

**Returnerar:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Anger beständigheten för en ActiveX-kontroll när den metod som används för beständighet är antingen PersistStream, PersistStreamInit eller PersistStorage.

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
>      YourMethodHere(control.getActiveXControlBinary()); //Använd din egen metod för att hantera ActiveX-egenskaper som lagras i dess binära fil
>  }
> ```

**Returnerar:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar grund-sliden. Skrivskyddad [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar presentationen. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
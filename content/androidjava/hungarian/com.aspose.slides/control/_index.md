---
title: Control
second_title: Aspose.Slides Androidhoz Java API referenciával
description: ActiveX vezérlőt képvisel.
type: docs
url: /hu/com.aspose.slides/control/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

ActiveX vezérlőt reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPersistence()](#getPersistence--) | Megkapja a módszert, amellyel az ActiveX control tulajdonságait tárolják. |
| [getName()](#getName--) | Lekérdezi vagy beállítja ennek a control nevét. |
| [setName(String value)](#setName-java.lang.String-) | Lekérdezi vagy beállítja ennek a control nevét. |
| [getClassId()](#getClassId--) | Lekérdezi a class id-t ennek a control-nek. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Lekérdezi a class id-t ennek a control-nek. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Visszaad egy Control image fill properties objektumot. |
| [getFrame()](#getFrame--) | Visszaadja vagy beállítja a control keretét. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Visszaadja vagy beállítja a control keretét. |
| [getProperties()](#getProperties--) | Visszaad egy ActiveX tulajdonságok gyűjteményét. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Meghatározza egy ActiveX control állandóságát, amikor a perzisztálásra használt módszer a PersistStream, PersistStreamInit vagy PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Megkapja a módszert, amellyel az ActiveX control tulajdonságait tárolják. Csak olvasható [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //Használja a saját módszerét az ActiveX tulajdonságok kezeléséhez, amelyek bináris fájlban vannak tárolva
>  }
> ```


**Visszatér:**
int
### getName() {#getName--}
```
public final String getName()
```

Lekérdezi vagy beállítja ennek a control nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Lekérdezi vagy beállítja ennek a control nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Lekérdezi ennek a control class id-jét. Csak olvasható java.util.UUID.

**Visszatér:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Lekérdezi ennek a control class id-jét. Csak olvasható java.util.UUID.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.UUID |  |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Visszaad egy Control image fill properties objektumot. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatér:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Visszaadja vagy beállítja a control keretét. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Visszatér:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Visszaadja vagy beállítja a control keretét. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Visszaad egy ActiveX tulajdonságok gyűjteményét. Csak olvasható [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Megjegyzés: Az Aspose.Slides csak XML alapú ActiveX tulajdonságokat támogat. Ha a tulajdonságok bináris formátumban vannak tárolva, ez a tulajdonság null értéket ad vissza.

**Visszatér:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Meghatározza egy ActiveX control állandóságát, amikor a perzisztálásra használt módszer a PersistStream, PersistStreamInit vagy PersistStorage.

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
>      YourMethodHere(control.getActiveXControlBinary()); //Használja a saját módszerét az ActiveX tulajdonságok kezeléséhez, amelyek bináris fájlban vannak tárolva
>  }
> ```


**Visszatér:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja az alap slide-ot. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a prezentációt. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)
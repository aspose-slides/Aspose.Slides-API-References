---
title: Control
second_title: Aspose.Slides Java API referencia
description: ActiveX vezérlőt ábrázol.
type: docs
url: /hu/com.aspose.slides/control/
---
**Öröklés:**  
java.lang.Object, com.aspose.slides.DomObject

**Az összes megvalósított interfész:**  
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)  
```
public class Control extends DomObject<ControlCollection> implements IControl
```

ActiveX vezérlőt ábrázol.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPersistence()](#getPersistence--) | Lekéri a módszert, amelyet az ActiveX vezérlő tulajdonságainak tárolásához használnak. |
| [getName()](#getName--) | Lekéri vagy beállítja ennek a vezérlőnek a nevét. |
| [setName(String value)](#setName-java.lang.String-) | Lekéri vagy beállítja ennek a vezérlőnek a nevét. |
| [getClassId()](#getClassId--) | Lekéri a vezérlő osztályazonosítóját. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Lekéri a vezérlő osztályazonosítóját. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Visszatér a Control kép kitöltési tulajdonság objektummal. |
| [getFrame()](#getFrame--) | Visszatér vagy beállítja a vezérlő keretét. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Visszatér vagy beállítja a vezérlő keretét. |
| [getProperties()](#getProperties--) | Visszatér egy ActiveX tulajdonságok gyűjteményével. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Megadja egy ActiveX vezérlő állapot megőrzését, amikor a mentés módszere a PersistStream, PersistStreamInit vagy a PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Lekéri a módszert, amelyet az ActiveX vezérlő tulajdonságainak tárolásához használnak. Csak olvasható [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //Használja saját módszerét a bináris fájlban tárolt ActiveX tulajdonságok kezeléséhez
>  }
> ```

**Visszatér:**  
int
### getName() {#getName--}
```
public final String getName()
```

Lekéri vagy beállítja ennek a vezérlőnek a nevét. Olvasás/írás String.

**Visszatér:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Lekéri vagy beállítja ennek a vezérlőnek a nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Lekéri a vezérlő class id-ját. Csak olvasható java.util.UUID.

**Visszatér:**  
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Lekéri a vezérlő class id-ját. Csak olvasható java.util.UUID.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Visszatér a Control kép kitöltési tulajdonság objektummal. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatér:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Visszatér vagy beállítja a vezérlő keretét. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Visszatér:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Visszatér vagy beállítja a vezérlő keretét. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Visszatér egy ActiveX tulajdonságok gyűjteményével. Csak olvasható [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Megjegyzés: Az Aspose.Slides csak XML alapú ActiveX tulajdonságokat támogat. Ha a tulajdonságok bináris formátumban vannak tárolva, ez a tulajdonság null értéket ad vissza.

**Visszatér:**  
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Megadja egy ActiveX vezérlő állapot megőrzését, amikor a mentés módszere a PersistStream, PersistStreamInit vagy a PersistStorage.

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
>      YourMethodHere(control.getActiveXControlBinary()); //Használja saját módszerét a bináris fájlban tárolt ActiveX tulajdonságok kezeléséhez
>  }
> ```


**Visszatér:**  
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszatér az alap diára. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszatér:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszatér a prezentációra. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**  
[IPresentation](../../com.aspose.slides/ipresentation)
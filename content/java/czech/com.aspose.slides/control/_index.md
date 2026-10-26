---
title: Control
second_title: Aspose.Slides pro Java API Reference
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

Reprezentuje ActiveX ovládací prvek.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPersistence()](#getPersistence--) | Získává metodu používanou k ukládání vlastností ActiveX ovládacího prvku. |
| [getName()](#getName--) | Získává nebo nastavuje název tohoto ovládacího prvku. |
| [setName(String value)](#setName-java.lang.String-) | Získává nebo nastavuje název tohoto ovládacího prvku. |
| [getClassId()](#getClassId--) | Získává ID třídy tohoto ovládacího prvku. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Získává ID třídy tohoto ovládacího prvku. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Vrací objekt vlastností výplně obrázku ovládacího prvku. |
| [getFrame()](#getFrame--) | Vrací nebo nastavuje rámec ovládacího prvku. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Vrací nebo nastavuje rámec ovládacího prvku. |
| [getProperties()](#getProperties--) | Vrací kolekci ActiveX vlastností. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Určuje perzistenci ActiveX ovládacího prvku, pokud je metoda perzistence buď PersistStream, PersistStreamInit nebo PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Získává metodu používanou k ukládání vlastností ActiveX ovládacího prvku. Pouze pro čtení [PersistenceType](../../com.aspose.slides/persistencetype).

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

Získává nebo nastavuje název tohoto ovládacího prvku. Čtení/zápis String.

**Vrací:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Získává nebo nastavuje název tohoto ovládacího prvku. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Získává ID třídy tohoto ovládacího prvku. Pouze pro čtení java.util.UUID.

**Vrací:**
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Získává ID třídy tohoto ovládacího prvku. Pouze pro čtení java.util.UUID.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Vrací objekt vlastností výplně obrázku ovládacího prvku. Pouze pro čtení [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Vrací:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Vrací nebo nastavuje rámec ovládacího prvku. Čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Vrací:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Vrací nebo nastavuje rámec ovládacího prvku. Čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Vrací kolekci ActiveX vlastností. Pouze pro čtení [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Poznámka: Aspose.Slides podporuje pouze XML-založené ActiveX vlastnosti. Pokud jsou vlastnosti uloženy v binárním formátu, tato vlastnost vrátí null.

**Vrací:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Určuje perzistenci ActiveX ovládacího prvku, pokud je metoda perzistence buď PersistStream, PersistStreamInit nebo PersistStorage.

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

Vrací základní snímek. Pouze pro čtení [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací prezentaci. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
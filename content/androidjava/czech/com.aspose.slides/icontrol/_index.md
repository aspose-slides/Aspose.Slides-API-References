---
title: IControl
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje ActiveX ovládací prvek.
type: docs
url: /cs/com.aspose.slides/icontrol/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Reprezentuje ActiveX ovládací prvek.
## Metody

| Metoda | Popis |
| --- | --- |
| [getName()](#getName--) | Vrací název tohoto ovládacího prvku. |
| [setName(String value)](#setName-java.lang.String-) | Vrací název tohoto ovládacího prvku. |
| [getClassId()](#getClassId--) | Získává ID třídy tohoto ovládacího prvku. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Vrací objekt vlastností výplně obrázku ControlEx. |
| [getFrame()](#getFrame--) | Vrací nebo nastavuje rámec ovládacího prvku. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Vrací nebo nastavuje rámec ovládacího prvku. |
| [getProperties()](#getProperties--) | Vrací kolekci vlastností ActiveX. |
| [getPersistence()](#getPersistence--) | Získává metodu používanou k uložení vlastností ovládacího prvku ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Určuje persistenci ovládacího prvku ActiveX, když metoda použitá k uložení je buď PersistStream, PersistStreamInit nebo PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

Vrací název tohoto ovládacího prvku. Číst/Zapisovat String.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Vrací název tohoto ovládacího prvku. Číst/Zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Získává ID třídy tohoto ovládacího prvku. Pouze pro čtení java.util.UUID.

**Vrací:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Vrací objekt vlastností výplně obrázku ControlEx. Pouze pro čtení [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Vrací:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Vrací nebo nastavuje rámec ovládacího prvku. Číst/Zapisovat [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Vrací:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Vrací nebo nastavuje rámec ovládacího prvku. Číst/Zapisovat [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Vrací kolekci vlastností ActiveX. Pouze pro čtení [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Vrací:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Získává metodu používanou k uložení vlastností ovládacího prvku ActiveX. Pouze pro čtení [PersistenceType](../../com.aspose.slides/persistencetype).

**Vrací:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Určuje persistenci ovládacího prvku ActiveX, když metoda použitá k uložení je buď PersistStream, PersistStreamInit nebo PersistStorage.

**Vrací:**
byte[]
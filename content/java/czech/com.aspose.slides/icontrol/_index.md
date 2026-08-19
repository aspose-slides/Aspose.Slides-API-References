---
title: IControl
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Reprezentuje ActiveX ovládací prvek.
type: docs
url: /cs/com.aspose.slides/icontrol/
---
**Všechny implementované rozhraní:**
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
| [getClassId()](#getClassId--) | Získá ID třídy tohoto ovládacího prvku. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Vrací objekt vlastností výplně obrázku ControlEx. |
| [getFrame()](#getFrame--) | Vrací nebo nastavuje rámec ovládacího prvku. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Vrací nebo nastavuje rámec ovládacího prvku. |
| [getProperties()](#getProperties--) | Vrací kolekci vlastností ActiveX. |
| [getPersistence()](#getPersistence--) | Získá metodu používanou k ukládání vlastností ActiveX ovládacího prvku. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Specifikuje trvalost ActiveX ovládacího prvku, když metoda použitá k uchování je buď PersistStream, PersistStreamInit nebo PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

Vrací název tohoto ovládacího prvku. Čtení/zápis String.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Vrací název tohoto ovládacího prvku. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Získá ID třídy tohoto ovládacího prvku. Pouze pro čtení java.util.UUID.

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

Vrací nebo nastavuje rámec ovládacího prvku. Čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Vrací:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Vrací nebo nastavuje rámec ovládacího prvku. Čtení/zápis [IShapeFrame](../../com.aspose.slides/ishapeframe).

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

Získá metodu používanou k ukládání vlastností ActiveX ovládacího prvku. Pouze pro čtení [PersistenceType](../../com.aspose.slides/persistencetype).

**Vrací:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Specifikuje trvalost ActiveX ovládacího prvku, když metoda použitá k uchování je buď PersistStream, PersistStreamInit nebo PersistStorage.

**Vrací:**
byte[]
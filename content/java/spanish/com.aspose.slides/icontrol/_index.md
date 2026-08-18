---
title: IControl
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un control ActiveX.
type: docs
url: /es/com.aspose.slides/icontrol/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Representa un control ActiveX.
## Métodos

| Método | Descripción |
| --- | --- |
| [getName()](#getName--) | Devuelve el nombre de este control. |
| [setName(String value)](#setName-java.lang.String-) | Devuelve el nombre de este control. |
| [getClassId()](#getClassId--) | Obtiene el id de clase de este control. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Devuelve el objeto de propiedades de relleno de imagen de ControlEx. |
| [getFrame()](#getFrame--) | Devuelve o establece el marco del control. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Devuelve o establece el marco del control. |
| [getProperties()](#getProperties--) | Devuelve una colección de propiedades ActiveX. |
| [getPersistence()](#getPersistence--) | Obtiene el método usado para almacenar propiedades del control ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Especifica la persistencia de un control ActiveX cuando el método usado para persistir es PersistStream, PersistStreamInit o PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```


Devuelve el nombre de este control. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Devuelve el nombre de este control. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```


Obtiene el id de clase de este control. Solo lectura java.util.UUID.

**Devuelve:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Devuelve el objeto de propiedades de relleno de imagen de ControlEx. Solo lectura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Devuelve:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


Devuelve o establece el marco del control. Lectura/escritura [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Devuelve:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```


Devuelve o establece el marco del control. Lectura/escritura [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```


Devuelve una colección de propiedades ActiveX. Solo lectura [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Devuelve:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```


Obtiene el método usado para almacenar propiedades del control ActiveX. Solo lectura [PersistenceType](../../com.aspose.slides/persistencetype).

**Devuelve:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```


Especifica la persistencia de un control ActiveX cuando el método usado para persistir es PersistStream, PersistStreamInit o PersistStorage.

**Devuelve:**
byte[]
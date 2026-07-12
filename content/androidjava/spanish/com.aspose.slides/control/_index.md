---
title: Control
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un control ActiveX.
type: docs
url: /es/com.aspose.slides/control/
---
**Herencia:**  
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**  
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)  
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Representa un control ActiveX.

## Métodos

| Método | Descripción |
| --- | --- |
| [getPersistence()](#getPersistence--) | Obtiene el método utilizado para almacenar propiedades del control ActiveX. |
| [getName()](#getName--) | Obtiene o establece el nombre de este control. |
| [setName(String value)](#setName-java.lang.String-) | Obtiene o establece el nombre de este control. |
| [getClassId()](#getClassId--) | Obtiene el ID de clase de este control. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Obtiene el ID de clase de este control. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Devuelve el objeto de propiedades de relleno de imagen del control. |
| [getFrame()](#getFrame--) | Devuelve o establece el marco del control. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Devuelve o establece el marco del control. |
| [getProperties()](#getProperties--) | Devuelve una colección de propiedades ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Especifica la persistencia de un control ActiveX cuando el método usado para persistir es PersistStream, PersistStreamInit o PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Obtiene el método utilizado para almacenar propiedades del control ActiveX. Solo lectura [PersistenceType](../../com.aspose.slides/persistencetype).

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
>      YourMethodHere(control.getActiveXControlBinary()); //Use su propio método para gestionar las propiedades ActiveX almacenadas en su archivo binario
>  }
> ```


**Devuelve:**  
int

### getName() {#getName--}
```
public final String getName()
```

Obtiene o establece el nombre de este control. Lectura/escritura String.

**Devuelve:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Obtiene o establece el nombre de este control. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Obtiene el ID de clase de este control. Solo lectura java.util.UUID.

**Devuelve:**  
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Obtiene el ID de clase de este control. Solo lectura java.util.UUID.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Devuelve el objeto de propiedades de relleno de imagen del control. Solo lectura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Devuelve:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Devuelve o establece el marco del control. Lectura/escritura [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Devuelve:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Devuelve o establece el marco del control. Lectura/escritura [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Devuelve una colección de propiedades ActiveX. Solo lectura [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Nota: Aspose.Slides solo admite propiedades ActiveX basadas en XML. Si las propiedades se almacenan en formato binario, esta propiedad devolverá null.

**Devuelve:**  
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Especifica la persistencia de un control ActiveX cuando el método usado para persistir es PersistStream, PersistStreamInit o PersistStorage.

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
>      YourMethodHere(control.getActiveXControlBinary()); //Use su propio método para gestionar las propiedades ActiveX almacenadas en su archivo binario
>  }
> ```


**Devuelve:**  
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva base. Solo lectura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Devuelve:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**  
[IPresentation](../../com.aspose.slides/ipresentation)
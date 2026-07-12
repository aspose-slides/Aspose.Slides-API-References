---
title: IControlCollection
second_title: Aspose.Slides para Android vía referencia de API Java
description: Una colección de controles ActiveX.
type: docs
url: /es/com.aspose.slides/icontrolcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Una colección de controles ActiveX.
## Métodos

| Método | Descripción |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Elimina un control ActiveX de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina un control ActiveX almacenado en la posición especificada de la colección. |
| [clear()](#clear--) | Elimina todos los controles de la colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve un control en la posición especificada. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Crea y agrega un nuevo control a la colección. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```


Elimina un control ActiveX de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Un control a eliminar. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Elimina un control ActiveX almacenado en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del control a eliminar. |

### clear() {#clear--}
```
public abstract void clear()
```


Elimina todos los controles de la colección.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```


Devuelve un control en la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de un control. |

**Devuelve:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```


Crea y agrega un nuevo control a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| controlType | int | Tipo de control a agregar. |
| x | float | La coordenada X del lado izquierdo del marco de la forma. |
| y | float | La coordenada Y del lado superior del marco de la forma. |
| width | float | El ancho del marco de la forma. |
| height | float | La altura del marco de la forma. |

**Devuelve:**
[IControl](../../com.aspose.slides/icontrol) - Control creado [IControl](../../com.aspose.slides/icontrol).
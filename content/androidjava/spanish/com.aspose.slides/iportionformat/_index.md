---
title: IPortionFormat
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Esta clase contiene las propiedades de formato de la porción de texto.
type: docs
url: /es/com.aspose.slides/iportionformat/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Esta clase contiene las propiedades de formato de la porción de texto. A diferencia de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), todas las propiedades de esta clase son escribibles.

--------------------

Esta clase se usa para devolver y manipular las propiedades de formato de la porción de texto definidas para la porción particular. Esto significa que no se aplica herencia al obtener los valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".

Para obtener los valores de los parámetros de formato efectivos, incluidas las herencias, necesita usar el método [getEffective](../../com.aspose.slides/iportionformat\#getEffective) que devuelve una instancia de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Métodos

| Método | Descripción |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Devuelve o establece el identificador del marcador. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Devuelve o establece el identificador del marcador. |
| [getSmartTagClean()](#getSmartTagClean--) | Determina si la etiqueta inteligente debe limpiarse. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determina si la etiqueta inteligente debe limpiarse. |
| [getEffective()](#getEffective--) | Obtiene los datos de formato de porción efectivos con la herencia aplicada. |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Devuelve o establece el identificador del marcador. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Devuelve o establece el identificador del marcador. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Determina si la etiqueta inteligente debe limpiarse. No se aplica herencia. Lectura/escritura boolean.

**Devuelve:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Determina si la etiqueta inteligente debe limpiarse. No se aplica herencia. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Obtiene los datos de formato de porción efectivos con la herencia aplicada.

**Devuelve:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
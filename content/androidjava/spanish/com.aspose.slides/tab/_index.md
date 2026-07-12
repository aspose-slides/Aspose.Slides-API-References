---
title: Tab
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa una tabulación para un texto.
type: docs
url: /es/com.aspose.slides/tab/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Representa una tabulación para un texto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Crea un nuevo Tab |
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Devuelve o establece la posición de una tabulación. |
| [setPosition(double value)](#setPosition-double-) | Devuelve o establece la posición de una tabulación. |
| [getAlignment()](#getAlignment--) | Devuelve o establece el estilo de alineación de una tabulación. |
| [setAlignment(int value)](#setAlignment-int-) | Devuelve o establece el estilo de alineación de una tabulación. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compara la instancia actual con otro objeto del mismo tipo. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


Crea un nuevo Tab

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | double | Posición de la tabulación. |
| align | int | Alineación. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versión. Solo lectura long.

**Devuelve:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```


Devuelve o establece la posición de una tabulación. Asignar esta propiedad puede cambiar el índice de la tabulación en la colección e invalidar el enumerador. Lectura/escritura double.

**Devuelve:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


Devuelve o establece la posición de una tabulación. Asignar esta propiedad puede cambiar el índice de la tabulación en la colección e invalidar el enumerador. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Devuelve o establece el estilo de alineación de una tabulación. Lectura/escritura [TabAlignment](../../com.aspose.slides/tabalignment).

**Devuelve:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Devuelve o establece el estilo de alineación de una tabulación. Lectura/escritura [TabAlignment](../../com.aspose.slides/tabalignment).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Compara la instancia actual con otro objeto del mismo tipo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un objeto para comparar con esta instancia. |

**Devuelve:**
int - Un entero de 32 bits que indica el orden relativo de los comparandos. El valor devuelto tiene estos significados:

 *  < 0 - Esta instancia es menor que obj.
 *  = 0 - Esta instancia es igual a obj.
 *  > 0 - Esta instancia es mayor que obj.
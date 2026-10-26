---
title: ITabEffectiveData
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Objeto inmutable que contiene las propiedades de parada de tabulación del texto efectivo.
type: docs
url: /es/com.aspose.slides/itabeffectivedata/
---
**Todas las interfaces implementadas:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Objeto inmutable que contiene las propiedades de parada de tabulación del texto efectivo.

--------------------

Esta interfaz se usa como parte de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Métodos

| Método | Descripción |
| --- | --- |
| [getPosition()](#getPosition--) | Devuelve la posición de una tabulación. |
| [getAlignment()](#getAlignment--) | Devuelve el estilo de alineación de una tabulación. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Devuelve la posición de una tabulación. Asignar esta propiedad puede cambiar el índice de la tabulación en la colección e invalidar el Enumerador. Solo lectura double.

**Devuelve:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Devuelve el estilo de alineación de una tabulación. Solo lectura [TabAlignment](../../com.aspose.slides/tabalignment).

**Devuelve:**
int
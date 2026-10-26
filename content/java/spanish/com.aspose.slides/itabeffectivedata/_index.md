---
title: ITabEffectiveData
second_title: Referencia de API de Aspose.Slides para Java
description: Objeto inmutable que contiene las propiedades de parada de tabulación de los textos efectivos.
type: docs
url: /es/com.aspose.slides/itabeffectivedata/
---
**Todas las interfaces implementadas:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Objeto inmutable que contiene las propiedades de tabulación del texto efectivo.

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


Devuelve la posición de una tabulación. Asignar esta propiedad puede cambiar el índice de la tabulación en la colección e invalidar el Enumerator. Solo lectura double.

**Devuelve:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Devuelve el estilo de alineación de una tabulación. Solo lectura [TabAlignment](../../com.aspose.slides/tabalignment).

**Devuelve:**
int
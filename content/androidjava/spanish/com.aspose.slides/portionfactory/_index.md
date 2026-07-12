---
title: PortionFactory
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Permite crear porciones de prueba
type: docs
url: /es/com.aspose.slides/portionfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Permite crear porciones de prueba

--------------------

Para compatibilidad COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createPortion()](#createPortion--) | Crea una porción de texto vacía. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Crea una porción de texto a partir de la cadena especificada. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Crea una porción utilizando datos de una porción especificada. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Crea una porción de texto vacía.

**Devuelve:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Crea una porción de texto a partir de la cadena especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | java.lang.String | Cadena. |

**Devuelve:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Crea una porción utilizando datos de una porción especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Una porción a usar. |

**Devuelve:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
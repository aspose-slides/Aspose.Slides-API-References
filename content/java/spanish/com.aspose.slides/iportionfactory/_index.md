---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: Permite crear porciones de prueba
type: docs
url: /es/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Permite crear porciones de prueba

--------------------

Para compatibilidad con COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createPortion()](#createPortion--) | Crea una porción de texto vacía. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Crea una porción de texto a partir de la cadena especificada. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Crea una porción utilizando los datos de una porción especificada. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Crea una porción de texto vacía.

**Devuelve:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Crea una porción de texto a partir de la cadena especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | java.lang.String | String. |

**Devuelve:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Crea una porción utilizando los datos de una porción especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Una portion para usar. |

**Devuelve:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
---
title: IPortionFactory
second_title: Aspose.Slides para Android via Referencia de API Java
description: Permite crear porciones de prueba
type: docs
url: /es/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Permite crear porciones de prueba

--------------------

Para compatibilidad COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Crea una porción de texto vacía.

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Crea una porción de texto a partir de la cadena especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | java.lang.String | String. |

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Crea una porción utilizando los datos de una porción especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Una porción a usar. |

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
---
title: ITextStyle
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Propiedades de formato de estilo de texto.
type: docs
url: /es/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Propiedades de formato de estilo de texto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Si el nivel de estilo existe, lo devuelve; de lo contrario, devuelve null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Propiedades predeterminadas del párrafo. |
| [getEffective()](#getEffective--) | Obtiene los datos de formato de estilo de texto efectivos con la herencia aplicada. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Si el nivel de estilo existe, lo devuelve; de lo contrario, devuelve null.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice basado en cero del nivel. Debe estar en el intervalo 0..8. |

**Devuelve:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formato del nivel [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Propiedades predeterminadas del párrafo. Solo lectura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Devuelve:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Obtiene los datos de formato de estilo de texto efectivos con la herencia aplicada.

**Devuelve:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Un [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).
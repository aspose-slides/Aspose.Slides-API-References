---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objeto inmutable que contiene propiedades de estilo de texto efectivas.
type: docs
url: /es/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Objeto inmutable que contiene propiedades de estilo de texto efectivas.

--------------------

Esta interfaz se usa junto con la interfaz [ITextStyle](../../com.aspose.slides/itextstyle) para devolver valores de formato efectivos con la herencia aplicada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Devuelve el nivel del estilo efectivo. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Devuelve las propiedades de párrafo predeterminadas efectivas. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Devuelve el nivel del estilo efectivo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice basado en cero del nivel. Debe estar en el intervalo 0..8. |

**Devuelve:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Formato efectivo del nivel [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Devuelve las propiedades de párrafo predeterminadas efectivas. Solo lectura [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Devuelve:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)
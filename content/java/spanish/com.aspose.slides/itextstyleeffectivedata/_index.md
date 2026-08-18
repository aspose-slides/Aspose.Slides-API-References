---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objeto inmutable que contiene propiedades efectivas de estilo de texto.
type: docs
url: /es/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Objeto inmutable que contiene propiedades efectivas de estilo de texto.

--------------------

Esta interfaz se usa junto con la interfaz [ITextStyle](../../com.aspose.slides/itextstyle) para devolver valores de formato efectivos con herencia aplicada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Devuelve el nivel del estilo efectivo. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Devuelve las propiedades predeterminadas de párrafo efectivas. |
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

Devuelve propiedades predeterminadas de párrafo efectivas. Solo lectura [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Devuelve:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)
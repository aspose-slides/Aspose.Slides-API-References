---
title: PptxOptions
second_title: Aspose.Slides para Android a través de la referencia de API de Java
description: Representa opciones para guardar presentaciones OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
type: docs
url: /es/com.aspose.slides/pptxoptions/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas las interfaces implementadas:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Representa opciones para guardar presentaciones OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Crea una nueva instancia de PptxOptions |

## Métodos

| Método | Descripción |
| --- | --- |
| [getConformance()](#getConformance--) | Especifica la clase de conformidad a la que se ajusta el documento Presentation. |
| [setConformance(int value)](#setConformance-int-) | Especifica la clase de conformidad a la que se ajusta el documento Presentation. |
| [getZip64Mode()](#getZip64Mode--) | Especifica si se utiliza el formato ZIP64 para el documento Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Especifica si se utiliza el formato ZIP64 para el documento Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Especifica si la miniatura de la presentación se actualizará. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Especifica si la miniatura de la presentación se actualizará. |
| [getCompressionLevel()](#getCompressionLevel--) | Especifica el nivel de compresión utilizado al guardar el documento de presentación. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Especifica el nivel de compresión utilizado al guardar el documento de presentación. |

### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Crea una nueva instancia de PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Especifica la clase de conformidad a la que se ajusta el documento Presentation. El valor predeterminado es [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Devuelve:**
int

### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Especifica la clase de conformidad a la que se ajusta el documento Presentation. El valor predeterminado es [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

Especifica si se utiliza el formato ZIP64 para el documento Presentation. El valor predeterminado es [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
int

### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

Especifica si se utiliza el formato ZIP64 para el documento Presentation. El valor predeterminado es [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

Especifica si la miniatura de la presentación se actualizará. Lectura/escritura booleano. Valor predeterminado es **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Cuando el valor de la opción es **true**, se generará la nueva miniatura.

Cuando el valor de la opción es **false**, la miniatura actual se guardará tal cual.

**Devuelve:**
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Especifica si la miniatura de la presentación se actualizará. Lectura/escritura booleano. Valor predeterminado es **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Cuando el valor de la opción es **true**, se generará la nueva miniatura.

Cuando el valor de la opción es **false**, la miniatura actual se guardará tal cual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Especifica el nivel de compresión utilizado al guardar el documento de presentación. El valor predeterminado es [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Los niveles de compresión más altos producen archivos más pequeños, pero requieren más tiempo de procesamiento. La relación de compresión real depende del contenido de la presentación.

**Devuelve:**
int

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

Especifica el nivel de compresión utilizado al guardar el documento de presentación. El valor predeterminado es [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Los niveles de compresión más altos producen archivos más pequeños, pero requieren más tiempo de procesamiento. La relación de compresión real depende del contenido de la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
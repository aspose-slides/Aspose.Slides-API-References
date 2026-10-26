---
title: IPptxOptions
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa opciones para guardar presentaciones OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /es/com.aspose.slides/ipptxoptions/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Representa opciones para guardar presentaciones OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Métodos

| Method | Description |
| --- | --- |
| [getConformance()](#getConformance--) | Especifica la clase de conformidad a la que se ajusta el documento Presentation. |
| [setConformance(int value)](#setConformance-int-) | Especifica la clase de conformidad a la que se ajusta el documento Presentation. |
| [getZip64Mode()](#getZip64Mode--) | Especifica si se utiliza el formato ZIP64 para el documento Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Especifica si se utiliza el formato ZIP64 para el documento Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Especifica si la miniatura de la presentación se actualizará. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Especifica si la miniatura de la presentación se actualizará. |
| [getCompressionLevel()](#getCompressionLevel--) | Especifica el nivel de compresión usado al guardar el documento de presentación. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Especifica el nivel de compresión usado al guardar el documento de presentación. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```


Especifica la clase de conformidad a la que se ajusta el documento Presentation. El valor predeterminado es [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Devuelve:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```


Especifica la clase de conformidad a la que se ajusta el documento Presentation. El valor predeterminado es [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
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
public abstract void setZip64Mode(int value)
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```


Especifica si la miniatura de la presentación se actualizará. Booleano de lectura/escritura. El valor predeterminado es **true**.

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
public abstract void setRefreshThumbnail(boolean value)
```


Especifica si la miniatura de la presentación se actualizará. Booleano de lectura/escritura. El valor predeterminado es **true**.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```


Especifica el nivel de compresión usado al guardar el documento de presentación. El valor predeterminado es [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Los niveles de compresión más altos producen archivos más pequeños pero requieren más tiempo de procesamiento. La relación de compresión real depende del contenido de la presentación.

**Devuelve:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```


Especifica el nivel de compresión usado al guardar el documento de presentación. El valor predeterminado es [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Los niveles de compresión más altos producen archivos más pequeños pero requieren más tiempo de procesamiento. La relación de compresión real depende del contenido de la presentación.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
---
title: IPdfOptions
second_title: Aspose.Slides para la Referencia de API de Java
description: Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.
type: docs
url: /es/com.aspose.slides/ipdfoptions/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Especifica el tipo de compresión que se utilizará para todo el contenido textual del documento. |
| [setTextCompression(int value)](#setTextCompression-int-) | Especifica el tipo de compresión que se utilizará para todo el contenido textual del documento. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True para incrustar fuentes TrueType para los caracteres ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True para incrustar fuentes TrueType para los caracteres ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Devuelve o establece una matriz de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Devuelve o establece una matriz de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Determina si todos los caracteres de la fuente deben incrustarse o solo un subconjunto usado. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Determina si todos los caracteres de la fuente deben incrustarse o solo un subconjunto usado. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo en negrita. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo en negrita. |
| [getJpegQuality()](#getJpegQuality--) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. |
| [getCompliance()](#getCompliance--) | Nivel de conformidad deseado para el documento PDF generado. |
| [setCompliance(int value)](#setCompliance-int-) | Nivel de conformidad deseado para el documento PDF generado. |
| [getPassword()](#getPassword--) | Estableciendo la contraseña de usuario para proteger el documento PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Estableciendo la contraseña de usuario para proteger el documento PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True para convertir todos los metarchivos usados en una presentación a imágenes PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True para convertir todos los metarchivos usados en una presentación a imágenes PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True para dibujar un marco negro alrededor de cada diapositiva. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True para dibujar un marco negro alrededor de cada diapositiva. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Obtiene o establece el color transparente de la imagen. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Obtiene o establece el color transparente de la imagen. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Aplica el color transparente especificado a una imagen si es true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Aplica el color transparente especificado a una imagen si es true. |
| [getInkOptions()](#getInkOptions--) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. |
| [getIncludeOleData()](#getIncludeOleData--) | True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Especifica el tipo de compresión que se utilizará para todo el contenido textual del documento. Lectura/escritura [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

El valor predeterminado es [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Devuelve:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Especifica el tipo de compresión que se utilizará para todo el contenido textual del documento. Lectura/escritura [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

El valor predeterminado es [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. Si se establece en true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que llevará a un tamaño más pequeño del documento PDF resultante.

--------------------

La selección de la mejor relación de compresión de imágenes es costosa computacionalmente y consume una cantidad adicional de RAM, y esta opción es false por defecto.

--------------------

El valor predeterminado es false.

**Devuelve:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. Si se establece en true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que llevará a un tamaño más pequeño del documento PDF resultante.

--------------------

La selección de la mejor relación de compresión de imágenes es costosa computacionalmente y consume una cantidad adicional de RAM, y esta opción es false por defecto.

--------------------

El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True para incrustar fuentes TrueType para los caracteres ASCII 32-127. Las fuentes para códigos de caracteres superiores a 127 siempre se incrustan. Lectura/escritura boolean.

--------------------

El valor predeterminado es **true**.

**Devuelve:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True para incrustar fuentes TrueType para los caracteres ASCII 32-127. Las fuentes para códigos de caracteres superiores a 127 siempre se incrustan. Lectura/escritura boolean.

--------------------

El valor predeterminado es **true**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Devuelve:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Devuelve o establece una matriz de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes. Lectura/escritura String[].

**Devuelve:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Devuelve o establece una matriz de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes. Lectura/escritura String[].

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Determina si todos los caracteres de la fuente deben incrustarse o solo un subconjunto usado. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Determina si todos los caracteres de la fuente deben incrustarse o solo un subconjunto usado. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo en negrita. Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo en negrita. Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escritura byte.

--------------------

Solo tiene efecto cuando un documento contiene imágenes JPEG.

Utilice esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardarlo en formato PDF. El valor puede variar de 0 a 100, donde 0 significa la peor calidad pero máxima compresión y 100 la mejor calidad pero mínima compresión.

El valor predeterminado es **100**.

**Devuelve:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escritura byte.

--------------------

Solo tiene efecto cuando un documento contiene imágenes JPEG.

Utilice esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardarlo en formato PDF. El valor puede variar de 0 a 100, donde 0 significa la peor calidad pero máxima compresión y 100 la mejor calidad pero mínima compresión.

El valor predeterminado es **100**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Nivel de conformidad deseado para el documento PDF generado. Lectura/escritura [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

El valor predeterminado es [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Devuelve:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Nivel de conformidad deseado para el documento PDF generado. Lectura/escritura [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

El valor predeterminado es [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Estableciendo la contraseña de usuario para proteger el documento PDF. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Estableciendo la contraseña de usuario para proteger el documento PDF. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Vea [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Devuelve:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Vea [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True para convertir todos los metarchivos usados en una presentación a imágenes PNG. Lectura/escritura boolean.

--------------------

El valor predeterminado es **true**. El documento PDF puede contener gráficos vectoriales e imágenes raster. Si SaveMetafilesAsPng se establece en true, la imagen Metafile de origen se convierte a formato Png y se guarda en Pdf como imagen raster. Si SaveMetafilesAsPng se establece en false, la Metafile de origen se convierte a gráficos vectoriales Pdf. Cada enfoque tiene ventajas y desventajas. Por ejemplo, si la Metafile se convierte a PNG, puede producirse cierta pérdida de calidad durante el escalado del documento resultante. Si la Metafile se convierte a gráficos vectoriales Pdf, pueden aparecer problemas de rendimiento en la herramienta de visualización Pdf.

**Devuelve:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True para convertir todos los metarchivos usados en una presentación a imágenes PNG. Lectura/escritura boolean.

--------------------

El valor predeterminado es **true**. El documento PDF puede contener gráficos vectoriales e imágenes raster. Si SaveMetafilesAsPng se establece en true, la imagen Metafile de origen se convierte a formato Png y se guarda en Pdf como imagen raster. Si SaveMetafilesAsPng se establece en false, la Metafile de origen se convierte a gráficos vectoriales Pdf. Cada enfoque tiene ventajas y desventajas. Por ejemplo, si la Metafile se convierte a PNG, puede producirse cierta pérdida de calidad durante el escalado del documento resultante. Si la Metafile se convierte a gráficos vectoriales Pdf, pueden aparecer problemas de rendimiento en la herramienta de visualización Pdf.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. Lectura/escritura float.

Valor: El efecto de este parámetro depende de varios factores. El algoritmo intenta obtener el mejor tamaño de imagen de salida según el valor de la propiedad, el tamaño de la imagen original y el tamaño del marco de la imagen. El uso de valores de propiedad similares puede dar el mismo resultado. Se recomienda usar un paso de 16 o 32 para obtener un efecto visible.

--------------------

La propiedad afecta al tamaño del archivo, al tiempo de exportación y a la calidad de la imagen.

El valor predeterminado es **96**.

**Devuelve:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. Lectura/escritura float.

Valor: El efecto de este parámetro depende de varios factores. El algoritmo intenta obtener el mejor tamaño de imagen de salida según el valor de la propiedad, el tamaño de la imagen original y el tamaño del marco de la imagen. El uso de valores de propiedad similares puede dar el mismo resultado. Se recomienda usar un paso de 16 o 32 para obtener un efecto visible.

--------------------

La propiedad afecta al tamaño del archivo, al tiempo de exportación y a la calidad de la imagen.

El valor predeterminado es **96**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True para dibujar un marco negro alrededor de cada diapositiva. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True para dibujar un marco negro alrededor de cada diapositiva. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

Obtiene o establece el color transparente de la imagen.

Valor: El color del transparente de la imagen.

**Devuelve:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

Obtiene o establece el color transparente de la imagen.

Valor: El color del transparente de la imagen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Aplica el color transparente especificado a una imagen si es true.

**Devuelve:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Aplica el color transparente especificado a una imagen si es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. Solo lectura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Devuelve:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
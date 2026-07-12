---
title: PdfOptions
second_title: Referencia de API Java de Aspose.Slides para Android
description: Proporciona opciones que controlan cómo se guarda una presentación en formato PDF.
type: docs
url: /es/com.aspose.slides/pdfoptions/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas las interfaces implementadas:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Proporciona opciones que controlan cómo se guarda una presentación en formato PDF.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancia la clase PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Establece la calidad JPEG
>      pdfOptions.setJpegQuality((byte)90);
>      // Establece el comportamiento para metafiles
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Establece el nivel de compresión de texto
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Define el estándar PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Guarda la presentación como PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Instancia una clase Presentation que representa un archivo PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancia la clase PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Añade diapositivas ocultas
>      pdfOptions.setShowHiddenSlides(true);
>      // Guarda la presentación como PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Instancia un objeto Presentation que representa un archivo PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancia la clase PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Establece la contraseña PDF y los permisos de acceso
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Guarda la presentación como PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Instancia un objeto Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Estableciendo tipo y tamaño de diapositiva
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Constructor predeterminado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [getTextCompression()](#getTextCompression--) | Especifica el tipo de compresión a usar para todo el contenido textual en el documento. |
| [setTextCompression(int value)](#setTextCompression-int-) | Especifica el tipo de compresión a usar para todo el contenido textual en el documento. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Determina si Aspose.Slides incrustará fuentes comunes para texto ASCII (rango de códigos 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Determina si Aspose.Slides incrustará fuentes comunes para texto ASCII (rango de códigos 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Devuelve o establece una matriz de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Devuelve o establece una matriz de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Determina si todos los caracteres de la fuente deben incrustarse o solo el subconjunto utilizado. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Determina si todos los caracteres de la fuente deben incrustarse o solo el subconjunto utilizado. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo negrita. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo negrita. |
| [getJpegQuality()](#getJpegQuality--) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. |
| [getCompliance()](#getCompliance--) | Nivel deseado de conformidad para el documento PDF generado. |
| [setCompliance(int value)](#setCompliance-int-) | Nivel deseado de conformidad para el documento PDF generado. |
| [getPassword()](#getPassword--) | Estableciendo la contraseña de usuario para proteger el documento PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Estableciendo la contraseña de usuario para proteger el documento PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Contiene un conjunto de banderas que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Contiene un conjunto de banderas que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Verdadero para convertir todos los metafiles usados en una presentación a imágenes PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Verdadero para convertir todos los metafiles usados en una presentación a imágenes PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Verdadero para dibujar un marco negro alrededor de cada diapositiva. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Verdadero para dibujar un marco negro alrededor de cada diapositiva. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Obtiene o establece el color transparente de la imagen. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Obtiene o establece el color transparente de la imagen. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Aplica el color transparente especificado a una imagen si es verdadero. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Aplica el color transparente especificado a una imagen si es verdadero. |
| [getIncludeOleData()](#getIncludeOleData--) | Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Constructor predeterminado.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. Solo lectura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Devuelve:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Devuelve:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```


Especifica el tipo de compresión a usar para todo el contenido textual en el documento. Lectura/escritura [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

El valor predeterminado es [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Devuelve:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```


Especifica el tipo de compresión a usar para todo el contenido textual en el documento. Lectura/escritura [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

El valor predeterminado es [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```


Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. Si se establece en true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que producirá un documento PDF resultante de menor tamaño.

--------------------

La selección de la relación de compresión de imagen más eficaz es computacionalmente costosa y requiere una cantidad adicional de RAM, y esta opción es false por defecto.

--------------------

El valor predeterminado es false.

**Devuelve:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```


Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. Si se establece en true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que producirá un documento PDF resultante de menor tamaño.

--------------------

La selección de la relación de compresión de imagen más eficaz es computacionalmente costosa y requiere una cantidad adicional de RAM, y esta opción es false por defecto.

--------------------

El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```


Determina si Aspose.Slides incrustará fuentes comunes para texto ASCII (rango de códigos 33..127). Las fuentes para códigos de caracteres mayores que 127 siempre se incrustan. La lista de fuentes comunes incluye las 14 fuentes base de PDF y fuentes adicionales especificadas por el usuario. Lectura/escritura boolean.

--------------------

El valor predeterminado es **true**.

**Devuelve:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```


Determina si Aspose.Slides incrustará fuentes comunes para texto ASCII (rango de códigos 33..127). Las fuentes para códigos de caracteres mayores que 127 siempre se incrustan. La lista de fuentes comunes incluye las 14 fuentes base de PDF y fuentes adicionales especificadas por el usuario. Lectura/escritura boolean.

--------------------

El valor predeterminado es **true**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```


Devuelve o establece una matriz de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes. Lectura/escritura String[].

**Devuelve:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```


Devuelve o establece una matriz de nombres de familias de fuentes definidos por el usuario que Aspose.Slides debe considerar comunes. Lectura/escritura String[].

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```


Determina si todos los caracteres de la fuente deben incrustarse o solo el subconjunto utilizado. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```


Determina si todos los caracteres de la fuente deben incrustarse o solo el subconjunto utilizado. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```


Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo negrita. Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```


Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo negrita. Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```


Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escritura byte.

--------------------

Solo tiene efecto cuando el documento contiene imágenes JPEG.

Utilice esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardarlo en formato PDF. El valor puede variar de 0 a 100, donde 0 significa la peor calidad pero máxima compresión y 100 la mejor calidad pero mínima compresión.

El valor predeterminado es **100**.

**Devuelve:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```


Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escritura byte.

--------------------

Solo tiene efecto cuando el documento contiene imágenes JPEG.

Utilice esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardarlo en formato PDF. El valor puede variar de 0 a 100, donde 0 significa la peor calidad pero máxima compresión y 100 la mejor calidad pero mínima compresión.

El valor predeterminado es **100**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Nivel deseado de conformidad para el documento PDF generado. Lectura/escritura [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

El valor predeterminado es [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Devuelve:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Nivel deseado de conformidad para el documento PDF generado. Lectura/escritura [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

El valor predeterminado es [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Estableciendo la contraseña de usuario para proteger el documento PDF. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Estableciendo la contraseña de usuario para proteger el documento PDF. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```


Contiene un conjunto de banderas que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Ver [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final void setAccessPermissions(int value)
```


Contiene un conjunto de banderas que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Ver [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final boolean getSaveMetafilesAsPng()
```


Verdadero para convertir todos los metafiles usados en una presentación a imágenes PNG. Lectura/escritura boolean.

--------------------

El valor predeterminado es **true**. Un documento PDF puede contener gráficos vectoriales e imágenes rasterizadas. Si SaveMetafilesAsPng se establece en true, la imagen Metafile de origen se convierte a formato PNG y se guarda en el PDF como imagen rasterizada. Si SaveMetafilesAsPng se establece en false, el Metafile de origen se convierte a gráficos vectoriales PDF. Cada enfoque tiene ventajas y desventajas. Por ejemplo, si el Metafile se convierte a PNG, es posible que se produzca alguna pérdida de calidad durante el escalado del documento resultante. Si el Metafile se convierte a gráficos vectoriales PDF, pueden producirse problemas de rendimiento en la herramienta de visualización de PDF.

**Devuelve:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


Verdadero para convertir todos los metafiles usados en una presentación a imágenes PNG. Lectura/escritura boolean.

--------------------

El valor predeterminado es **true**. Un documento PDF puede contener gráficos vectoriales e imágenes rasterizadas. Si SaveMetafilesAsPng se establece en true, la imagen Metafile de origen se convierte a formato PNG y se guarda en el PDF como imagen rasterizada. Si SaveMetafilesAsPng se establece en false, el Metafile de origen se convierte a gráficos vectoriales PDF. Cada enfoque tiene ventajas y desventajas. Por ejemplo, si el Metafile se convierte a PNG, es posible que se produzca alguna pérdida de calidad durante el escalado del documento resultante. Si el Metafile se convierte a gráficos vectoriales PDF, pueden producirse problemas de rendimiento en la herramienta de visualización de PDF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```


Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. Lectura/escritura float.

Valor: El efecto de este parámetro depende de varios factores. El algoritmo intenta obtener el mejor tamaño de imagen de salida según el valor de la propiedad, el tamaño de la imagen origen y el tamaño del marco de la imagen. Usar valores de propiedad similares puede dar el mismo resultado. Se recomienda usar pasos de 16 o 32 para obtener un efecto visible.

--------------------

La propiedad afecta al tamaño del archivo, al tiempo de exportación y a la calidad de la imagen.

El valor predeterminado es **96**.

**Devuelve:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```


Devuelve o establece un valor que determina la resolución de las imágenes dentro del documento PDF. Lectura/escritura float.

Valor: El efecto de este parámetro depende de varios factores. El algoritmo intenta obtener el mejor tamaño de imagen de salida según el valor de la propiedad, el tamaño de la imagen origen y el tamaño del marco de la imagen. Usar valores de propiedad similares puede dar el mismo resultado. Se recomienda usar pasos de 16 o 32 para obtener un efecto visible.

--------------------

La propiedad afecta al tamaño del archivo, al tiempo de exportación y a la calidad de la imagen.

El valor predeterminado es **96**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


Verdadero para dibujar un marco negro alrededor de cada diapositiva. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


Verdadero para dibujar un marco negro alrededor de cada diapositiva. Lectura/escritura boolean.

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```


Obtiene o establece el color transparente de la imagen.

Valor: El color de la transparencia de la imagen.

**Devuelve:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```


Obtiene o establece el color transparente de la imagen.

Valor: El color de la transparencia de la imagen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```


Aplica el color transparente especificado a una imagen si es verdadero.

**Devuelve:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```


Aplica el color transparente especificado a una imagen si es verdadero.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```


Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura boolean.

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
public final void setIncludeOleData(boolean value)
```


Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura boolean.

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
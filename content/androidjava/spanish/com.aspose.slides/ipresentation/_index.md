---
title: IPresentation
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Documento de presentación
type: docs
url: /es/com.aspose.slides/ipresentation/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Documento de presentación
## Métodos

| Método | Descripción |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Devuelve o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Devuelve o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el gestor HeaderFooter de la presentación. |
| [getProtectionManager()](#getProtectionManager--) | Obtiene el gestor de los permisos de esta presentación. |
| [getSlides()](#getSlides--) | Devuelve una lista de todas las diapositivas definidas en la presentación. |
| [getSections()](#getSections--) | Devuelve una lista de todas las secciones de diapositivas definidas en la presentación. |
| [getSlideSize()](#getSlideSize--) | Devuelve el objeto de tamaño de diapositiva. |
| [getNotesSize()](#getNotesSize--) | Devuelve el objeto de tamaño de diapositiva de notas. |
| [getLayoutSlides()](#getLayoutSlides--) | Devuelve una lista de todas las diapositivas de diseño definidas en la presentación. |
| [getMasters()](#getMasters--) | Devuelve una lista de todas las diapositivas maestras definidas en la presentación. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Devuelve el gestor maestro de notas. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Devuelve el gestor maestro de folletos. |
| [getFontsManager()](#getFontsManager--) | Devuelve el gestor de fuentes. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Devuelve el estilo de texto predeterminado para formas. |
| [getCommentAuthors()](#getCommentAuthors--) | Devuelve la colección de autores de comentarios. |
| [getDocumentProperties()](#getDocumentProperties--) | Devuelve el objeto DocumentProperties que contiene propiedades estándar y personalizadas del documento. |
| [getImages()](#getImages--) | Devuelve la colección de todas las imágenes en la presentación. |
| [getAudios()](#getAudios--) | Devuelve la colección de todos los archivos de audio incrustados en la presentación. |
| [getVideos()](#getVideos--) | Devuelve la colección de todos los archivos de video incrustados en la presentación. |
| [getCustomData()](#getCustomData--) | Devuelve los datos personalizados de la presentación. |
| [getVbaProject()](#getVbaProject--) | Obtiene el proyecto VBA con macros de la presentación. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Obtiene el proyecto VBA con macros de la presentación. |
| [getSourceFormat()](#getSourceFormat--) | Devuelve información sobre el formato desde el cual se cargó la presentación. |
| [getMasterTheme()](#getMasterTheme--) | Devuelve el tema maestro de la presentación. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Proporciona fácil acceso a todos los hipervínculos contenidos en todas las diapositivas de la presentación (no en maestras, de diseño o de notas). |
| [getViewProperties()](#getViewProperties--) | Obtiene las propiedades de vista de toda la presentación. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Representa el número de la primera diapositiva en la presentación. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Representa el número de la primera diapositiva en la presentación. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Devuelve todas las partes de datos personalizados en la presentación. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Devuelve la colección de firmas usadas para firmar la presentación. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Devuelve la colección de etiquetas de sensibilidad aplicadas al documento de la presentación. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Guarda todas las diapositivas de una presentación en un flujo con el formato especificado. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado y con opciones adicionales. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Guarda todas las diapositivas de una presentación en un flujo con el formato especificado y con opciones adicionales. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Guarda diapositivas especificadas de una presentación en un archivo con el formato especificado. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Guarda diapositivas especificadas de una presentación en un archivo con el formato especificado. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Guarda diapositivas especificadas de una presentación en un flujo con el formato especificado. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Guarda diapositivas especificadas de una presentación en un flujo con el formato especificado. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan marcado XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Devuelve objetos Thumbnail IImage para diapositivas especificadas de una presentación. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación con escalado personalizado. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Devuelve objetos Thumbnail Image para diapositivas especificadas de una presentación con escalado personalizado. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación con tamaño especificado. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Devuelve objetos Thumbnail Image para diapositivas especificadas de una presentación con tamaño especificado. |
| [getSlideById(long id)](#getSlideById-long-) | Devuelve una diapositiva, MasterSlide o LayoutSlide por Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une porciones con el mismo formato en todos los párrafos de todas las formas aceptables en todas las diapositivas. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Reemplaza todas las ocurrencias del texto especificado con otro texto especificado. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Reemplaza todas las coincidencias de la expresión regular con la cadena especificada. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Devuelve o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. Tiempo de creación de este objeto Presentation por defecto. Lectura/escritura java.util.Date.

**Devuelve:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Devuelve o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. Tiempo de creación de este objeto Presentation por defecto. Lectura/escritura java.util.Date.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Devuelve el gestor HeaderFooter de la presentación. Solo lectura [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Devuelve:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Obtiene el gestor de los permisos de esta presentación. Solo lectura [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Devuelve:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Devuelve una lista de todas las diapositivas definidas en la presentación. Solo lectura [ISlideCollection](../../com.aspose.slides/islidecollection).

**Devuelve:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Devuelve una lista de todas las secciones de diapositivas definidas en la presentación. Solo lectura [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Devuelve:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Devuelve el objeto de tamaño de diapositiva. Solo lectura [ISlideSize](../../com.aspose.slides/islidesize).

**Devuelve:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Devuelve el objeto de tamaño de diapositiva de notas. Solo lectura [INotesSize](../../com.aspose.slides/inotessize).

**Devuelve:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Devuelve una lista de todas las diapositivas de diseño definidas en la presentación. Solo lectura [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Puede acceder a la API alternativa para agregar/insertar/eliminar/clonar diapositivas de diseño usando la propiedad IMasterSlide.LayoutSlides.

**Devuelve:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Devuelve una lista de todas las diapositivas maestras definidas en la presentación. Solo lectura [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Devuelve:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Devuelve el gestor maestro de notas. Solo lectura [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Devuelve:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Devuelve el gestor maestro de folletos. Solo lectura [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Devuelve:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Devuelve el gestor de fuentes. Solo lectura [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Devuelve:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Devuelve el estilo de texto predeterminado para formas. Solo lectura [ITextStyle](../../com.aspose.slides/itextstyle).

**Devuelve:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Devuelve la colección de autores de comentarios. Solo lectura [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Devuelve:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Devuelve el objeto DocumentProperties que contiene propiedades estándar y personalizadas del documento. Solo lectura [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Devuelve:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Devuelve la colección de todas las imágenes en la presentación. Solo lectura [IImageCollection](../../com.aspose.slides/iimagecollection).

**Devuelve:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Devuelve la colección de todos los archivos de audio incrustados en la presentación. Solo lectura [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Devuelve:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Devuelve la colección de todos los archivos de video incrustados en la presentación. Solo lectura [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Devuelve:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Devuelve los datos personalizados de la presentación. Solo lectura [ICustomData](../../com.aspose.slides/icustomdata).

**Devuelve:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Obtiene el proyecto VBA con macros de la presentación. Lectura/escritura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Devuelve:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Obtiene el proyecto VBA con macros de la presentación. Lectura/escritura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Devuelve información sobre el formato desde el cual se cargó la presentación. Solo lectura [SourceFormat](../../com.aspose.slides/sourceformat).

**Devuelve:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Devuelve el tema maestro de la presentación. Solo lectura [IMasterTheme](../../com.aspose.slides/imastertheme).

**Devuelve:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Proporciona fácil acceso a todos los hipervínculos contenidos en todas las diapositivas de la presentación (no en maestras, de diseño o de notas). Solo lectura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Devuelve:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Obtiene las propiedades de vista de toda la presentación. Solo lectura [IViewProperties](../../com.aspose.slides/iviewproperties).

**Devuelve:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Representa el número de la primera diapositiva en la presentación. Lectura/escritura int.

**Devuelve:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Representa el número de la primera diapositiva en la presentación. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Devuelve todas las partes de datos personalizados en la presentación. Solo lectura ICustomXmlPart[].

**Devuelve:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Devuelve la colección de firmas usadas para firmar la presentación. Solo lectura [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Devuelve la colección de etiquetas de sensibilidad aplicadas al documento de la presentación. Solo lectura [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Imprime las etiquetas aplicadas
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Añade la nueva etiqueta
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Obtiene el Id de la etiqueta de sensibilidad de la política
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Obtiene el identificador del sitio Azure AD de la política
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Guarda todas las diapositivas de una presentación en un archivo con el formato especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | java.lang.String | Ruta al archivo creado. |
| format | int | Formato de los datos exportados. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Guarda todas las diapositivas de una presentación en un flujo con el formato especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida. |
| format | int | Formato de los datos exportados. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Guarda todas las diapositivas de una presentación en un archivo con el formato especificado y con opciones adicionales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | java.lang.String | Ruta al archivo creado. |
| format | int | Formato de los datos exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opciones adicionales de formato. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Guarda todas las diapositivas de una presentación en un flujo con el formato especificado y con opciones adicionales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida. |
| format | int | Formato de los datos exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opciones adicionales de formato. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Guarda diapositivas especificadas de una presentación en un archivo con el formato especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | java.lang.String | Ruta al archivo creado. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| format | int | Formato de los datos exportados. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Guarda diapositivas especificadas de una presentación en un archivo con el formato especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | java.lang.String | Ruta al archivo creado. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| format | int | Formato de los datos exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opciones adicionales de formato. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Guarda diapositivas especificadas de una presentación en un flujo con el formato especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| format | int | Formato de los datos exportados. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Guarda diapositivas especificadas de una presentación en un flujo con el formato especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| format | int | Formato de los datos exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opciones adicionales de formato. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan marcado XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Las opciones de formato XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |

**Devuelve:**
com.aspose.slides.IImage[] - objetos IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Devuelve objetos Thumbnail IImage para diapositivas especificadas de una presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |

**Devuelve:**
com.aspose.slides.IImage[] - objetos IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación con escalado personalizado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |
| scaleX | float | Valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scaleY | float | Valor por el cual escalar este Thumbnail en la dirección del eje y. |

**Devuelve:**
com.aspose.slides.IImage[] - objetos Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Devuelve objetos Thumbnail Image para diapositivas especificadas de una presentación con escalado personalizado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| scaleX | float | Valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scaleY | float | Valor por el cual escalar este Thumbnail en la dirección del eje y. |

**Devuelve:**
com.aspose.slides.IImage[] - objetos IImage.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Devuelve objetos Thumbnail Image para todas las diapositivas de una presentación con tamaño especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamaño de la imagen a crear. |

**Devuelve:**
com.aspose.slides.IImage[] - objetos IImage.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Devuelve objetos Thumbnail Image para diapositivas especificadas de una presentación con tamaño especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamaño de la imagen a crear. |

**Devuelve:**
com.aspose.slides.IImage[] - objetos IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Devuelve una diapositiva, MasterSlide o LayoutSlide por Id.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | long | Id de una diapositiva. |

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - objeto IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Une porciones con el mismo formato en todos los párrafos de todas las formas aceptables en todas las diapositivas.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Resalta todas las coincidencias del texto de muestra con el color especificado.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // resaltando todas las ocurrencias separadas de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | El texto a resaltar. |
| highlightColor | java.lang.Integer | El color para resaltar el texto. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Resalta todas las coincidencias del texto de muestra con el color especificado.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // resaltando todas las ocurrencias separadas de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | El texto a resaltar. |
| highlightColor | java.lang.Integer | El color para resaltar el texto. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opciones de búsqueda de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | El objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Resalta todas las coincidencias de la expresión regular con el color especificado.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // resaltando todas las ocurrencias separadas de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | java.util.regex.Pattern | La expresión regular java.util.regex.Pattern para obtener cadenas a resaltar. |
| highlightColor | java.lang.Integer | El color para resaltar el texto. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | El objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Reemplaza todas las ocurrencias del texto especificado con otro texto especificado.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Reemplaza todas las ocurrencias separadas de 'the' con '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldText | java.lang.String | La cadena a reemplazar. |
| newText | java.lang.String | La cadena que reemplaza todas las ocurrencias de oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opciones de búsqueda de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | El objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Reemplaza todas las ocurrencias separadas de 'the' con '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | java.util.regex.Pattern | La expresión regular java.util.regex.Pattern para obtener cadenas a reemplazar. |
| newText | java.lang.String | La cadena que reemplaza todas las ocurrencias de las cadenas a reemplazar. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | El objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
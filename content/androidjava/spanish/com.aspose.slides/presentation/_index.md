---
title: Presentation
second_title: Aspose.Slides para Android a través de la Referencia de la API Java
description: Representa una presentación de Microsoft PowerPoint.
type: docs
url: /es/com.aspose.slides/presentation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Representa una presentación de Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Instanciar un objeto Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation();
>  try {
>      // Obtener la primera diapositiva
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Agregar una autoshape de tipo línea
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Guardar el archivo de presentación.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Cargar cualquier archivo compatible en Presentation e.g. ppt, pptx, odp etc.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Guardar el archivo de presentación.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructores

| Constructor | Description |
| --- | --- |
| [Presentation()](#Presentation--) | Este constructor crea una nueva presentación desde cero. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Este constructor crea una nueva presentación desde cero. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Este constructor es el mecanismo principal para leer una presentación existente. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Este constructor es el mecanismo principal para leer una presentación existente. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Este constructor obtiene la ruta del archivo fuente desde donde se leen los contenidos de la presentación. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Este constructor obtiene la ruta del archivo fuente desde donde se leen los contenidos de la presentación. |

## Métodos

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Obtiene o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Obtiene o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Obtiene el administrador actual de HeaderFooter. |
| [getProtectionManager()](#getProtectionManager--) | Obtiene el gestor de permisos de esta presentación. |
| [getSlides()](#getSlides--) | Devuelve una lista de todas las diapositivas definidas en la presentación. |
| [getSections()](#getSections--) | Devuelve una lista de todas las secciones de diapositivas definidas en la presentación. |
| [getSlideSize()](#getSlideSize--) | Devuelve el objeto de tamaño de diapositiva. |
| [getNotesSize()](#getNotesSize--) | Devuelve el objeto de tamaño de diapositiva de notas. |
| [getLayoutSlides()](#getLayoutSlides--) | Devuelve una lista de todas las diapositivas de diseño definidas en la presentación. |
| [getMasters()](#getMasters--) | Devuelve una lista de todas las diapositivas maestras definidas en la presentación. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Devuelve el gestor de notas maestra. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Devuelve el gestor de folleto maestro. |
| [getFontsManager()](#getFontsManager--) | Devuelve el gestor de fuentes. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Devuelve el estilo de texto predeterminado para formas. |
| [getCommentAuthors()](#getCommentAuthors--) | Devuelve la colección de autores de comentarios. |
| [getDocumentProperties()](#getDocumentProperties--) | Devuelve el objeto DocumentProperties que contiene propiedades estándar y personalizadas del documento. |
| [getImages()](#getImages--) | Devuelve la colección de todas las imágenes en la presentación. |
| [getAudios()](#getAudios--) | Devuelve la colección de todos los archivos de audio incrustados en la presentación. |
| [getVideos()](#getVideos--) | Devuelve la colección de todos los archivos de vídeo incrustados en la presentación. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Devuelve la configuración de presentación de diapositivas para la presentación. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Devuelve la colección de firmas usadas para firmar la presentación. |
| [getCustomData()](#getCustomData--) | Devuelve los datos personalizados de la presentación. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Devuelve todas las partes de datos personalizados en la presentación. |
| [getVbaProject()](#getVbaProject--) | Obtiene o establece el proyecto VBA con macros de la presentación. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Obtiene o establece el proyecto VBA con macros de la presentación. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Proporciona acceso fácil a todos los hipervínculos contenidos en todas las diapositivas de la presentación (no en maestras, diseños o notas). |
| [getViewProperties()](#getViewProperties--) | Obtiene las propiedades de vista de toda la presentación. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Representa el número de la primera diapositiva en la presentación. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Representa el número de la primera diapositiva en la presentación. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Devuelve la colección de etiquetas de sensibilidad aplicadas al documento de la presentación. |
| [getSlideById(long id)](#getSlideById-long-) | Devuelve una Slide, MasterSlide o LayoutSlide por Id. |
| [getSourceFormat()](#getSourceFormat--) | Devuelve información sobre el formato desde el cual se cargó la presentación. |
| [getMasterTheme()](#getMasterTheme--) | Devuelve el tema maestro. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Guarda todas las diapositivas de una presentación en un flujo en el formato especificado. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Guarda todas las diapositivas de una presentación en un archivo con el formato especificado y con opciones adicionales. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Guarda todas las diapositivas de una presentación en un flujo en el formato especificado y con opciones adicionales. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan marcado XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Devuelve objetos Image para todas las diapositivas de una presentación. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Devuelve objetos Image de miniatura para las diapositivas especificadas de una presentación. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Devuelve objetos Image de miniatura para todas las diapositivas de una presentación con escalado personalizado. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Devuelve objetos Image de miniatura para las diapositivas especificadas de una presentación con escalado personalizado. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Devuelve objetos Image de miniatura para todas las diapositivas de una presentación con tamaño especificado. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Devuelve objetos Image de miniatura para las diapositivas especificadas de una presentación con el tamaño especificado. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Guarda las diapositivas especificadas de una presentación en un flujo en el formato especificado manteniendo el número de página. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Guarda las diapositivas especificadas de una presentación en un flujo en el formato especificado manteniendo el número de página. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fusiona porciones con el mismo formato en todos los párrafos de todas las formas aceptables en todas las diapositivas. |
| [dispose()](#dispose--) | Libera todos los recursos usados por este objeto Presentation. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación principal de un texto. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Resalta todas las coincidencias del texto de ejemplo con el color especificado. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Resalta todas las coincidencias del texto de ejemplo con el color especificado. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Reemplaza todas las apariciones del texto especificado por otro texto especificado. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Reemplaza todas las coincidencias de la expresión regular por la cadena especificada. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Este constructor crea una nueva presentación desde cero. La presentación creada tiene una diapositiva vacía.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Este constructor crea una nueva presentación desde cero. La presentación creada tiene una diapositiva vacía.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opciones de carga adicionales. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Este constructor es el mecanismo principal para leer una presentación existente.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo de entrada. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Este constructor es el mecanismo principal para leer una presentación existente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo de entrada. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opciones de carga adicionales. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Este constructor obtiene la ruta del archivo fuente desde donde se leen los contenidos de la presentación.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | java.lang.String | Archivo de entrada. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Este constructor obtiene la ruta del archivo fuente desde donde se leen los contenidos de la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| file | java.lang.String | Archivo de entrada. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opciones de carga adicionales. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Obtiene o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. Por defecto, la hora de creación de este objeto Presentation. Lectura/escritura java.util.Date.

**Devuelve:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Obtiene o establece la fecha y hora que sustituirá el contenido de los campos de fecha y hora. Por defecto, la hora de creación de este objeto Presentation. Lectura/escritura java.util.Date.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Devuelve el administrador actual de HeaderFooter. Solo lectura [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // La propiedad IsFooterVisible se usa para indicar que no está presente un marcador de posición de pie de página en la diapositiva.
>      {
>          headerFooterManager.setFooterVisibility(true); // El método SetFooterVisibility se usa para hacer visible el marcador de posición de pie de página de la diapositiva.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // La propiedad IsSlideNumberVisible se usa para indicar que no está presente un marcador de posición de número de página en la diapositiva.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // El método SetSlideNumberVisibility se usa para hacer visible el marcador de posición de número de página de la diapositiva.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // La propiedad IsDateTimeVisible se usa para indicar que no está presente un marcador de posición de fecha y hora en la diapositiva.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // El método SetFooterVisibility se usa para hacer visible el marcador de posición de fecha y hora en la diapositiva.
>      }
>      headerFooterManager.setFooterText("Footer text"); // El método SetFooterText se usa para establecer texto en el marcador de posición de pie de página de la diapositiva.
>      headerFooterManager.setDateTimeText("Date and time text"); // El método SetDateTimeText se usa para establecer texto en el marcador de posición de fecha y hora de la diapositiva.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // El método SetFooterAndChildFootersVisibility se usa para hacer visible una diapositiva maestra y todos los marcadores de posición de pies de página hijos.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // El método SetSlideNumberAndChildSlideNumbersVisibility se usa para hacer visible una diapositiva maestra y todos los marcadores de posición de número de página hijos.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // El método SetDateTimeAndChildDateTimesVisibility se usa para hacer visible una diapositiva maestra y todos los marcadores de posición de fecha y hora hijos.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // El método SetFooterAndChildFootersText se usa para establecer texto en la diapositiva maestra y todos los marcadores de posición de pies de página hijos.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // El método SetDateTimeAndChildDateTimesText se usa para establecer texto en la diapositiva maestra y todos los marcadores de posición de fecha y hora hijos.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Obtiene el gestor de permisos para esta presentación. Solo lectura [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Devuelve:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Devuelve una lista de todas las diapositivas definidas en la presentación. Solo lectura [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Instanciar la clase Presentation que representa el archivo de presentación
>  Presentation pres = new Presentation();
>  try
>  {
>      // Establecer el color de fondo de la primera ISlide a azul
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Instanciar la clase Presentation que representa el archivo de presentación
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Establecer el fondo con una imagen
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Establecer la imagen
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // Añadir la imagen a la colección de imágenes de la presentación
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // Guardar la presentación en disco
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Instanciar la clase Presentation para cargar el archivo de presentación fuente
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Aplicar transición de tipo círculo en la diapositiva 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Aplicar transición de tipo peine en la diapositiva 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Guardar la presentación en disco
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Instanciar la clase Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Aplicar transición de tipo círculo en la diapositiva 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Establecer el tiempo de transición a 3 segundos
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Aplicar transición de tipo peine en la diapositiva 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Establecer el tiempo de transición a 5 segundos
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Aplicar transición de tipo zoom en la diapositiva 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Establecer el tiempo de transición a 7 segundos
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Guardar la presentación en disco
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Devuelve una lista de todas las secciones de diapositivas definidas en la presentación. Solo lectura [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 terminará en newSlide2 y después de ella comenzará section2
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Devuelve el objeto de tamaño de diapositiva. Solo lectura [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Instanciar un objeto Presentation que representa un archivo de presentación
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Establecer el tamaño de diapositiva de las presentaciones generadas al del origen
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // El método SetSize se usa para establecer el tamaño de diapositiva con contenido escalado para asegurar ajuste
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // El método SetSize se usa para establecer el tamaño de diapositiva maximizando el tamaño del contenido
>          // Guardar la presentación en disco
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // Tamaño de papel A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Devuelve el objeto de tamaño de diapositiva de notas. Solo lectura [INotesSize](../../com.aspose.slides/inotessize).

**Devuelve:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Devuelve una lista de todas las diapositivas de diseño definidas en la presentación. Solo lectura [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Puedes acceder a la API alternativa para agregar/insertar/eliminar/clonar diapositivas de diseño mediante la propiedad IMasterSlide.LayoutSlides.

**Devuelve:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Devuelve una lista de todas las diapositivas maestras definidas en la presentación. Solo lectura [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Instanciar la clase Presentation que representa el archivo de presentación
>  Presentation pres = new Presentation();
>  try
>  {
>      // Establecer el color de fondo del Master ISlide a verde bosque
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Escribir la presentación en disco
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instanciar la clase Presentation que representa el archivo de presentación
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Intentar buscar por tipo de diapositiva de diseño
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Situación en la que una presentación no contiene algunos tipos de diseños.
>          // El archivo de presentación solo contiene tipos de diseño en blanco y personalizados.
>          // Sin embargo, las diapositivas de diseño con tipos personalizados tienen nombres de diapositiva diferentes,
>          // como "Title", "Title and Content", etc. Y es posible usar estos
>          // nombres para la selección de diapositivas de diseño.
>          // También es posible usar el conjunto de tipos de forma de marcador de posición. Por ejemplo,
>          // La diapositiva de título solo debería tener el tipo de marcador de posición Title, etc.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Agregar diapositiva vacía con la diapositiva de diseño añadida
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Guardar presentación
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Devuelve:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Devuelve el gestor de notas maestro. Solo lectura [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Devuelve:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Devuelve el gestor de folleto maestro. Solo lectura [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Devuelve:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Devuelve el gestor de fuentes. Solo lectura [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Cargar la presentación
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Cargar la fuente origen a reemplazar
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Guardar la presentación
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Devuelve el estilo de texto predeterminado para formas. Solo lectura [ITextStyle](../../com.aspose.slides/itextstyle).

**Devuelve:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Devuelve la colección de autores de comentarios. Solo lectura [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Devuelve:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Devuelve el objeto DocumentProperties que contiene propiedades estándar y personalizadas del documento. Solo lectura [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Devuelve:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Devuelve la colección de todas las imágenes en la presentación. Solo lectura [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // crea una nueva presentación a la que se añadirá la imagen.
>  Presentation pres = new Presentation();
>  try
>  {
>      // supongamos que tenemos el archivo de imagen grande que queremos incluir en la presentación
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Añadamos la imagen a la presentación - elegimos el comportamiento KeepLocked porque
>          // NO pretendemos acceder al archivo "largeImage.png".
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Guarda la presentación. Mientras se genera una presentación grande, el consumo de memoria
>          // se mantiene bajo durante el ciclo de vida del objeto pres.
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // Añade la imagen a la presentación
>          IPPImage image = pres.getImages().addImage(fos);
>          // Crea un marco de imagen en la diapositiva 1 basado en la imagen añadida previamente
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Devuelve la colección de todos los archivos de audio incrustados en la presentación. Solo lectura [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

Devuelve la colección de todos los archivos de vídeo incrustados en la presentación. Solo lectura [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instanciar la clase Presentation que representa el PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Obtener la primera diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Incrustar video dentro de la presentación
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Añadir marco de video
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Asignar el video al marco de video
>      vf.setEmbeddedVideo(vid);
>      // Establecer modo de reproducción y volumen del video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Escribir el archivo PPTX en disco
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Crear una nueva presentación a la que se añadirá el video
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Añadamos el video a la presentación - elegimos el comportamiento KeepLocked porque
>          // no pretendemos acceder al archivo "veryLargeVideo.avi".
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Guardar la presentación. Mientras se genera una presentación grande, el consumo de memoria
>          // se mantiene bajo durante el ciclo de vida del objeto pres.
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Bloquear el archivo fuente y NO cargarlo en memoria
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Crear una instancia de Presentation, bloquea el archivo "hugePresentationWithAudiosAndVideos.pptx".
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Guardemos cada video en un archivo. Para evitar un alto uso de memoria, necesitamos un búfer que se utilizará
>      // para transferir los datos del flujo de video de la presentación a un flujo para un nuevo archivo de video.
>      byte[] buffer = new byte[81024];
>      // Iterar a través de los videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Abrir el flujo de video de la presentación. Tenga en cuenta que intencionalmente evitamos acceder a propiedades
>          // como video.BinaryData - porque esta propiedad devuelve un array de bytes que contiene el video completo, lo que entonces
>          // causa que los bytes se carguen en memoria. Usamos video.GetStream, que devuelve un Stream y NO
>          //  requiere cargar todo el video en la memoria.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // El consumo de memoria permanecerá bajo sin importar el tamaño del video o de la presentación,
>      }
>      // Si es necesario, puede aplicar los mismos pasos para archivos de audio.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //añadir marco de video
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //cargar miniatura
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instanciar un objeto Presentation que representa un archivo de presentación
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Devuelve:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Devuelve la configuración de presentación de diapositivas para la presentación.

**Devuelve:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
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
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Devuelve los datos personalizados de la presentación. Solo lectura [ICustomData](../../com.aspose.slides/icustomdata).

**Devuelve:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Devuelve todas las partes de datos personalizados en la presentación. Solo lectura ICustomXmlPart[].

--------------------

> ```
> Los siguientes ejemplos muestran cómo eliminar todas las partes XML personalizadas de una presentación de PowerPoint.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Recorrer todas las partes XML personalizadas
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
com.aspose.slides.ICustomXmlPart[]

### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Obtiene o establece el proyecto VBA con macros de la presentación. Lectura/escritura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Devuelve:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Obtiene o establece el proyecto VBA con macros de la presentación. Lectura/escritura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Proporciona acceso fácil a todos los hipervínculos contenidos en todas las diapositivas de la presentación (no en maestras, diseños o notas). Solo lectura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Devuelve:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Obtiene las propiedades de vista de toda la presentación. Solo lectura [IViewProperties](../../com.aspose.slides/iviewproperties).

**Devuelve:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Representa el número de la primera diapositiva en la presentación.

**Devuelve:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

Representa el número de la primera diapositiva en la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Devuelve la colección de etiquetas de sensibilidad aplicadas al documento de la presentación. Solo lectura [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Imprimir las etiquetas aplicadas
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Añadir la nueva etiqueta
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Obtener el Id de la etiqueta de sensibilidad de la política
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Obtener el identificador del sitio Azure AD de la política
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

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Devuelve una Slide, MasterSlide o LayoutSlide por Id.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| id | long | Id de una diapositiva. |

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Devuelve información sobre el formato desde el cual se cargó la presentación. Solo lectura [SourceFormat](../../com.aspose.slides/sourceformat).

**Devuelve:**
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Devuelve el tema maestro. Solo lectura [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> Los siguientes ejemplos muestran cómo cambiar un efecto de tema alterando partes de los elementos de una presentación de PowerPoint.
>  
>  //Instanciar un objeto Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Guarda todas las diapositivas de una presentación en un archivo con el formato especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | java.lang.String | Ruta al archivo creado. |
| format | int | Formato de los datos exportados. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Guarda todas las diapositivas de una presentación en un flujo en el formato especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida. |
| format | int | Formato de los datos exportados. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Guarda todas las diapositivas de una presentación en un archivo con el formato especificado y con opciones adicionales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | java.lang.String | Ruta al archivo creado. |
| format | int | Formato de los datos exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opciones de formato adicionales. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Guarda todas las diapositivas de una presentación en un flujo en el formato especificado y con opciones adicionales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida. |
| format | int | Formato de los datos exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opciones de formato adicionales. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Opciones del formato XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

Devuelve objetos Image para todas las diapositivas de una presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones Tiff. |

**Devuelve:**
com.aspose.slides.IImage[] - Objetos Image.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Devuelve objetos Image de miniatura para las diapositivas especificadas de una presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones Tiff. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |

**Devuelve:**
com.aspose.slides.IImage[] - Objetos Image.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Devuelve objetos Image de miniatura para todas las diapositivas de una presentación con escalado personalizado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones Tiff. |
| scaleX | float | Valor por el que escalar la miniatura en la dirección del eje X. |
| scaleY | float | Valor por el que escalar la miniatura en la dirección del eje Y. |

**Devuelve:**
com.aspose.slides.IImage[] - Objetos Image.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Devuelve objetos Image de miniatura para las diapositivas especificadas de una presentación con escalado personalizado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones Tiff. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| scaleX | float | Valor por el que escalar la miniatura en la dirección del eje X. |
| scaleY | float | Valor por el que escalar la miniatura en la dirección del eje Y. |

**Devuelve:**
com.aspose.slides.IImage[] - Objetos Image.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Devuelve objetos Image de miniatura para todas las diapositivas de una presentación con el tamaño especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones Tiff. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamaño de la imagen a crear. |

**Devuelve:**
com.aspose.slides.IImage[] - Objetos Image.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Devuelve objetos Image de miniatura para las diapositivas especificadas de una presentación con el tamaño especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones Tiff. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamaño de la imagen a crear. |

**Devuelve:**
com.aspose.slides.IImage[] - Objetos Image.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | java.lang.String | Ruta al archivo creado. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| format | int | Formato de los datos exportados. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISSaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | java.lang.String | Ruta al archivo creado. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| format | int | Formato de los datos exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opciones de formato adicionales. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Guarda las diapositivas especificadas de una presentación en un flujo en el formato especificado manteniendo el número de página.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| format | int | Formato de los datos exportados. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Guarda las diapositivas especificadas de una presentación en un flujo en el formato especificado manteniendo el número de página.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida. |
| slides | int[] | Matriz con posiciones de diapositivas, comenzando desde 1. |
| format | int | Formato de los datos exportados. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opciones de formato adicionales. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Fusiona porciones con el mismo formato en todos los párrafos de todas las formas aceptables en todas las diapositivas.

### dispose() {#dispose--}
```
public final void dispose()
```

Libera todos los recursos usados por este objeto Presentation.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación principal de un texto. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Resalta todas las coincidencias del texto de ejemplo con el color especificado.

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
| highlightColor | java.lang.Integer | El color con el que resaltar el texto. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Resalta todas las coincidencias del texto de ejemplo con el color especificado.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // resaltando todas las ocurrencias separadas de 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | El texto a resaltar. |
| highlightColor | java.lang.Integer | El color con el que resaltar el texto. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opciones de búsqueda de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Resalta todas las coincidencias de la expresión regular con el color especificado.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // resaltando todas las palabras con 10 símbolos o más
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | java.util.regex.Pattern | La expresión regular java.util.regex.Pattern para obtener las cadenas a resaltar. |
| highlightColor | java.lang.Integer | El color con el que resaltar el texto. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Reemplaza todas las apariciones del texto especificado por otro texto especificado.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Reemplazar todas las ocurrencias separadas de 'the' con '***'
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
| newText | java.lang.String | La cadena que reemplazará todas las apariciones de oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opciones de búsqueda de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Reemplaza todas las coincidencias de la expresión regular por la cadena especificada.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Reemplazar todas las palabras con 10 símbolos o más con '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | java.util.regex.Pattern | La expresión regular java.util.regex.Pattern para obtener las cadenas a reemplazar. |
| newText | java.lang.String | La cadena que reemplazará todas las apariciones de las cadenas a reemplazar. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
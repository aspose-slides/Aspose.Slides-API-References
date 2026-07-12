---
title: SaveOptions
second_title: Aspose.Slides para Android vía API Java
description: Clase abstracta con opciones que controlan cómo se guarda una presentación.
type: docs
url: /es/com.aspose.slides/saveoptions/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Clase abstracta con opciones que controlan cómo se guarda una presentación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. |
| [getProgressCallback()](#getProgressCallback--) | Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Devuelve o establece la fuente utilizada cuando no se encuentra la fuente original. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Devuelve o establece la fuente utilizada cuando no se encuentra la fuente original. |
| [getGradientStyle()](#getGradientStyle--) | Devuelve o establece el estilo visual del degradado. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Devuelve o establece el estilo visual del degradado. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Especifica si se omiten los hipervínculos con llamadas a JavaScript al guardar la presentación. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Especifica si se omiten los hipervínculos con llamadas a JavaScript al guardar la presentación. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Leer/escribir [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Devuelve:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Leer/escribir [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje. Ver [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Devuelve:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje. Ver [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Devuelve o establece la fuente utilizada cuando no se encuentra la fuente original. Lectura/escritura String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Devuelve o establece la fuente utilizada cuando no se encuentra la fuente original. Lectura/escritura String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


Devuelve o establece el estilo visual del degradado. Leer/escribir [GradientStyle](../../com.aspose.slides/gradientstyle).

**Devuelve:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Devuelve o establece el estilo visual del degradado. Leer/escribir [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


Especifica si se omiten los hipervínculos con llamadas a JavaScript al guardar la presentación. Leer/escribir booleano. El valor predeterminado es false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Cuando esta propiedad se establece en true, los hipervínculos con llamadas a JavaScript se ignorarán al guardar.

Cuando esta propiedad se establece en false, se guardarán todos los hipervínculos.

**Devuelve:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


Especifica si se omiten los hipervínculos con llamadas a JavaScript al guardar la presentación. Leer/escribir booleano. El valor predeterminado es false.

--------------------

> ```
> Ejemplo:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Cuando esta propiedad se establece en true, los hipervínculos con llamadas a JavaScript se ignorarán al guardar.

Cuando esta propiedad se establece en false, se guardarán todos los hipervínculos.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
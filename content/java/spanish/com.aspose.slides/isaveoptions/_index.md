---
title: ISaveOptions
second_title: Aspose.Slides para Java API Reference
description: Opciones que controlan cómo se guarda una presentación.
type: docs
url: /es/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Opciones que controlan cómo se guarda una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. |
| [getProgressCallback()](#getProgressCallback--) | Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Devuelve o establece la fuente utilizada en caso de que la fuente origen no se encuentre. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Devuelve o establece la fuente utilizada en caso de que la fuente origen no se encuentre. |
| [getGradientStyle()](#getGradientStyle--) | Devuelve o establece el estilo visual del degradado. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Devuelve o establece el estilo visual del degradado. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returns:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje. Ver [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Returns:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

Representa un objeto de devolución de llamada para actualizaciones de progreso de guardado en porcentaje. Ver [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Devuelve o establece la fuente utilizada en caso de que la fuente origen no se encuentre. Lectura-escritura String.

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


**Returns:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Devuelve o establece la fuente utilizada en caso de que la fuente origen no se encuentre. Lectura-escritura String.

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


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```

Devuelve o establece el estilo visual del degradado. Lectura/escritura [GradientStyle](../../com.aspose.slides/gradientstyle).

**Returns:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

Devuelve o establece el estilo visual del degradado. Lectura/escritura [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lectura/escritura boolean. El valor predeterminado es false.

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


Cuando esta propiedad se establece en true, los hipervínculos con llamadas JavaScript se ignorarán al guardar.

Cuando esta propiedad se establece en false, todos los hipervínculos se guardarán.

**Returns:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lectura/escritura boolean. El valor predeterminado es false.

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

Cuando esta propiedad se establece en true, los hipervínculos con llamadas JavaScript se ignorarán al guardar.

Cuando esta propiedad se establece en false, todos los hipérvínculos se guardarán.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Opções que controlam como uma apresentação é salva.
type: docs
url: /pt/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Opções que controlam como uma apresentação é salva.
## Métodos

| Method | Description |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. |
| [getProgressCallback()](#getProgressCallback--) | Representa um objeto de retorno de chamada para atualizações de progresso de salvamento em porcentagem. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Representa um objeto de retorno de chamada para atualizações de progresso de salvamento em porcentagem. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada. |
| [getGradientStyle()](#getGradientStyle--) | Retorna ou define o estilo visual do gradiente. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Retorna ou define o estilo visual do gradiente. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/Gravação [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Retorna:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/Gravação [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```


Representa um objeto de retorno de chamada para atualizações de progresso de salvamento em porcentagem. Veja [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Retorna:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```


Representa um objeto de retorno de chamada para atualizações de progresso de salvamento em porcentagem. Veja [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


Retorna ou define a fonte usada caso a fonte de origem não seja encontrada. Leitura/Gravação String.

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

**Retorna:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


Retorna ou define a fonte usada caso a fonte de origem não seja encontrada. Leitura/Gravação String.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```


Retorna ou define o estilo visual do gradiente. Leitura/Gravação [GradientStyle](../../com.aspose.slides/gradientstyle).

**Retorna:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```


Retorna ou define o estilo visual do gradiente. Leitura/Gravação [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```


Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação. Leitura/Gravação boolean. O valor padrão é false.

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

Quando esta propriedade for definida como true, hyperlinks com chamadas JavaScript serão ignorados ao salvar.

Quando esta propriedade for definida como false, todos os hyperlinks serão salvos.

**Retorna:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```


Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação. Leitura/Gravação boolean. O valor padrão é false.

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

Quando esta propriedade for definida como true, hyperlinks com chamadas JavaScript serão ignorados ao salvar.

Quando esta propriedade for definida como false, todos os hyperlinks serão salvos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
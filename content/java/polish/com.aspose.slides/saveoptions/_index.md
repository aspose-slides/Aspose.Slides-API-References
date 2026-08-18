---
title: SaveOptions
second_title: Aspose.Slides dla Java – odniesienie API
description: Klasa abstrakcyjna z opcjami, które kontrolują sposób zapisywania prezentacji.
type: docs
url: /pl/com.aspose.slides/saveoptions/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Klasa abstrakcyjna z opcjami, które sterują tym, jak prezentacja jest zapisywana.
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. |
| [getProgressCallback()](#getProgressCallback--) | Reprezentuje obiekt zwrotny dla aktualizacji postępu zapisywania w procentach. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Reprezentuje obiekt zwrotny dla aktualizacji postępu zapisywania w procentach. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Zwraca lub ustawia czcionkę używaną, gdy nie znaleziono czcionki źródłowej. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Zwraca lub ustawia czcionkę używaną, gdy nie znaleziono czcionki źródłowej. |
| [getGradientStyle()](#getGradientStyle--) | Zwraca lub ustawia styl wizualny gradientu. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Zwraca lub ustawia styl wizualny gradientu. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczyt/zapis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Zwraca:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczyt/zapis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Reprezentuje obiekt zwrotny dla aktualizacji postępu zapisywania w procentach. Zobacz [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Zwraca:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Reprezentuje obiekt zwrotny dla aktualizacji postępu zapisywania w procentach. Zobacz [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Zwraca lub ustawia czcionkę używaną, gdy nie znaleziono czcionki źródłowej. Odczyt-zapis String.

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

**Zwraca:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Zwraca lub ustawia czcionkę używaną, gdy nie znaleziono czcionki źródłowej. Odczyt-zapis String.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


Zwraca lub ustawia styl wizualny gradientu. Odczyt/zapis [GradientStyle](../../com.aspose.slides/gradientstyle).

**Zwraca:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Zwraca lub ustawia styl wizualny gradientu. Odczyt/zapis [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczyt/zapis boolean. Domyślna wartość to false.

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

Gdy ta właściwość jest ustawiona na true, hiperłącza z wywołaniami JavaScript będą ignorowane podczas zapisywania.

Gdy ta właściwość jest ustawiona na false, wszystkie hiperłącza zostaną zapisane.

**Zwraca:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczyt/zapis boolean. Domyślna wartość to false.

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

Gdy ta właściwość jest ustawiona na true, hiperłącza z wywołaniami JavaScript będą ignorowane podczas zapisywania.

Gdy ta właściwość jest ustawiona na false, wszystkie hiperłącza zostaną zapisane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
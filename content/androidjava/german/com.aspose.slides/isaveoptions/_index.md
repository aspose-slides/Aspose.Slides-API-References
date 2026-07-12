---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /de/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Optionen, die steuern, wie eine Präsentation gespeichert wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. |
| [getProgressCallback()](#getProgressCallback--) | Stellt ein Callback-Objekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Stellt ein Callback-Objekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. |
| [getGradientStyle()](#getGradientStyle--) | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Rückgabe:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Gibt ein Objekt zurück oder legt es fest, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen/Schreiben [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

Stellt ein Callback-Objekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar. Siehe [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Rückgabe:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

Stellt ein Callback-Objekt für Fortschrittsaktualisierungen beim Speichern in Prozent dar. Siehe [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lesen/Schreiben String.

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


**Rückgabe:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Gibt die Schriftart zurück oder legt sie fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lesen/Schreiben String.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```

Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest. Lesen/Schreiben [GradientStyle](../../com.aspose.slides/gradientstyle).

**Rückgabe:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

Gibt den visuellen Stil des Farbverlaufs zurück oder legt ihn fest. Lesen/Schreiben [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lesen/Schreiben boolesch. Der Standardwert ist false.

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

Wenn diese Eigenschaft auf true gesetzt ist, werden Hyperlinks mit JavaScript-Aufrufen beim Speichern ignoriert.

Wenn diese Eigenschaft auf false gesetzt ist, werden alle Hyperlinks gespeichert.

**Rückgabe:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lesen/Schreiben boolesch. Der Standardwert ist false.

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

Wenn diese Eigenschaft auf true gesetzt ist, werden Hyperlinks mit JavaScript-Aufrufen beim Speichern ignoriert.

Wenn diese Eigenschaft auf false gesetzt ist, werden alle Hyperlinks gespeichert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
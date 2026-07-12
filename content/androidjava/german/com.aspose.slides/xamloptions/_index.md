---
title: XamlOptions
second_title: Aspose.Slides für Android über Java API Reference
description: Optionen, die steuern, wie ein XAML-Dokument gespeichert wird.
type: docs
url: /de/com.aspose.slides/xamloptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

Optionen, die steuern, wie ein XAML-Dokument gespeichert wird.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Erstellt die XamlOptions-Instanz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bestimmt, ob versteckte Folien exportiert werden. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bestimmt, ob versteckte Folien exportiert werden. |
| [getOutputSaver()](#getOutputSaver--) | Stellt eine Implementierung der IOutputSaver-Schnittstelle dar. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Stellt eine Implementierung der IOutputSaver-Schnittstelle dar. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```

Erstellt die XamlOptions-Instanz.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Bestimmt, ob versteckte Folien exportiert werden.

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

**Rückgabewert:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Bestimmt, ob versteckte Folien exportiert werden.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```

Stellt eine Implementierung der IOutputSaver-Schnittstelle dar.

**Rückgabewert:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```

Stellt eine Implementierung der IOutputSaver-Schnittstelle dar.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |
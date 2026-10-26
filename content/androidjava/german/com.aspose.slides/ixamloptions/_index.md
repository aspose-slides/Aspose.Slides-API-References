---
title: IXamlOptions
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Optionen, die steuern, wie ein XAML-Dokument gespeichert wird.
type: docs
url: /de/com.aspose.slides/ixamloptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
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
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Bestimmt, ob versteckte Folien exportiert werden. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Bestimmt, ob versteckte Folien exportiert werden. |
| [getOutputSaver()](#getOutputSaver--) | Stellt eine Implementierung der IOutputSaver-Schnittstelle dar. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Stellt eine Implementierung der IOutputSaver-Schnittstelle dar. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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

**Rückgabe:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
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
public abstract IXamlOutputSaver getOutputSaver()
```


Stellt eine Implementierung der IOutputSaver-Schnittstelle dar.

**Rückgabe:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


Stellt eine Implementierung der IOutputSaver-Schnittstelle dar.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |
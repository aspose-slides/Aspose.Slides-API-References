---
title: XamlOptions
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Opzioni che controllano come viene salvato un documento XAML.
type: docs
url: /it/com.aspose.slides/xamloptions/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

Opzioni che controllano come viene salvato un documento XAML.

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

## Costruttori

| Constructor | Descrizione |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Crea l'istanza XamlOptions. |
## Metodi

| Method | Descrizione |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina se le diapositive nascoste verranno esportate. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina se le diapositive nascoste verranno esportate. |
| [getOutputSaver()](#getOutputSaver--) | Rappresenta un'implementazione dell'interfaccia IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Rappresenta un'implementazione dell'interfaccia IOutputSaver. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


Crea l'istanza XamlOptions.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Determina se le diapositive nascoste verranno esportate.

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

**Restituisce:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


Determina se le diapositive nascoste verranno esportate.

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```


Rappresenta un'implementazione dell'interfaccia IOutputSaver.

**Restituisce:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


Rappresenta un'implementazione dell'interfaccia IOutputSaver.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |
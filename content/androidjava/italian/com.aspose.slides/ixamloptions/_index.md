---  
title: IXamlOptions  
second_title: Aspose.Slides per Android tramite Java API Reference  
description: Opzioni che controllano come viene salvato un documento XAML.  
type: docs  
url: /it/com.aspose.slides/ixamloptions/  
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
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
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina se le diapositive nascoste verranno esportate. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina se le diapositive nascoste verranno esportate. |
| [getOutputSaver()](#getOutputSaver--) | Rappresenta un'implementazione dell'interfaccia IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Rappresenta un'implementazione dell'interfaccia IOutputSaver. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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
public abstract void setExportHiddenSlides(boolean value)
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
public abstract IXamlOutputSaver getOutputSaver()
```

Rappresenta un'implementazione dell'interfaccia IOutputSaver.

**Restituisce:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```

Rappresenta un'implementazione dell'interfaccia IOutputSaver.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |
---
title: IXamlOptions
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir XAML belgesinin nasıl kaydedileceğini kontrol eden seçenekler.
type: docs
url: /tr/com.aspose.slides/ixamloptions/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

Bir XAML belgesinin nasıl kaydedileceğini kontrol eden seçenekler.

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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. |
| [getOutputSaver()](#getOutputSaver--) | IOutputSaver arayüzünün bir uygulanmasını temsil eder. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | IOutputSaver arayüzünün bir uygulanmasını temsil eder. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Gizli slaytların dışa aktarılıp aktarılmayacağını belirler.

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

**Dönüş Değeri:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


Gizli slaytların dışa aktarılıp aktarılmayacağını belirler.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```


IOutputSaver arayüzünün bir uygulanmasını temsil eder.

**Dönüş Değeri:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


IOutputSaver arayüzünün bir uygulanmasını temsil eder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |
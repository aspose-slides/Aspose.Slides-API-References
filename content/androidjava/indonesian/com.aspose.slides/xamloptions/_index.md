---
title: XamlOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Opsi yang mengontrol cara dokumen XAML disimpan.
type: docs
url: /id/com.aspose.slides/xamloptions/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
```

Opsi yang mengontrol cara dokumen XAML disimpan.

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
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Membuat instance XamlOptions. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Menentukan apakah slide tersembunyi akan diekspor. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Menentukan apakah slide tersembunyi akan diekspor. |
| [getOutputSaver()](#getOutputSaver--) | Mewakili sebuah implementasi antarmuka IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Mewakili sebuah implementasi antarmuka IOutputSaver. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


Membuat instance XamlOptions.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Menentukan apakah slide tersembunyi akan diekspor.

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

**Mengembalikan:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


Menentukan apakah slide tersembunyi akan diekspor.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public final IXamlOutputSaver getOutputSaver()
```


Mewakili sebuah implementasi antarmuka IOutputSaver.

**Mengembalikan:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


Mewakili sebuah implementasi antarmuka IOutputSaver.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |
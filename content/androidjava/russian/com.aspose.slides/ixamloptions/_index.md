---
title: IXamlOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Параметры, управляющие тем, как сохраняется документ XAML.
type: docs
url: /ru/com.aspose.slides/ixamloptions/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXamlOptions extends ISaveOptions
```

Параметры, управляющие тем, как сохраняется документ XAML.

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
## Методы
| Метод | Описание |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Определяет, будут ли экспортированы скрытые слайды. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Определяет, будут ли экспортированы скрытые слайды. |
| [getOutputSaver()](#getOutputSaver--) | Представляет реализацию интерфейса IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Представляет реализацию интерфейса IOutputSaver. |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Определяет, будут ли экспортированы скрытые слайды.

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

**Возвращаемое значение:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


Определяет, будут ли экспортированы скрытые слайды.

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getOutputSaver() {#getOutputSaver--}
```
public abstract IXamlOutputSaver getOutputSaver()
```


Представляет реализацию интерфейса IOutputSaver.

**Возвращаемое значение:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public abstract void setOutputSaver(IXamlOutputSaver value)
```


Представляет реализацию интерфейса IOutputSaver.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |
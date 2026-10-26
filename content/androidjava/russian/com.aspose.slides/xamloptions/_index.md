---
title: XamlOptions
second_title: Aspose.Slides для Android через справочник API Java
description: Опции, управляющие тем, как сохраняется документ XAML.
type: docs
url: /ru/com.aspose.slides/xamloptions/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Все реализованные интерфейсы:**
[com.aspose.slides.IXamlOptions](../../com.aspose.slides/ixamloptions)
```
public class XamlOptions extends SaveOptions implements IXamlOptions
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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XamlOptions()](#XamlOptions--) | Создает экземпляр XamlOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Определяет, будут ли экспортированы скрытые слайды. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Определяет, будут ли экспортированы скрытые слайды. |
| [getOutputSaver()](#getOutputSaver--) | Представляет реализацию интерфейса IOutputSaver. |
| [setOutputSaver(IXamlOutputSaver value)](#setOutputSaver-com.aspose.slides.IXamlOutputSaver-) | Представляет реализацию интерфейса IOutputSaver. |
### XamlOptions() {#XamlOptions--}
```
public XamlOptions()
```


Создает экземпляр XamlOptions.

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
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
public final void setExportHiddenSlides(boolean value)
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
public final IXamlOutputSaver getOutputSaver()
```


Представляет реализацию интерфейса IOutputSaver.

**Возвращаемое значение:**
[IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver)
### setOutputSaver(IXamlOutputSaver value) {#setOutputSaver-com.aspose.slides.IXamlOutputSaver-}
```
public final void setOutputSaver(IXamlOutputSaver value)
```


Представляет реализацию интерфейса IOutputSaver.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IXamlOutputSaver](../../com.aspose.slides/ixamloutputsaver) |  |
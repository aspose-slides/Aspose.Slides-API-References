---
title: ISwfOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате SWF.
type: docs
url: /ru/com.aspose.slides/iswfoptions/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате SWF.
## Методы

| Метод | Описание |
| --- | --- |
| [getCompressed()](#getCompressed--) | Указывает, следует ли сжимать сгенерированный документ SWF или нет. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Указывает, следует ли сжимать сгенерированный документ SWF или нет. |
| [getViewerIncluded()](#getViewerIncluded--) | Указывает, следует ли включать в сгенерированный документ SWF интегрированный просмотрщик документов или нет. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Указывает, следует ли включать в сгенерированный документ SWF интегрированный просмотрщик документов или нет. |
| [getShowPageBorder()](#getShowPageBorder--) | Указывает, следует ли отображать границу вокруг страниц. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Указывает, следует ли отображать границу вокруг страниц. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в сгенерированный документ. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в сгенерированный документ. |
| [getShowFullScreen()](#getShowFullScreen--) | Показать/скрыть кнопку полноэкранного режима. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Показать/скрыть кнопку полноэкранного режима. |
| [getShowPageStepper()](#getShowPageStepper--) | Показать/скрыть переключатель страниц. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Показать/скрыть переключатель страниц. |
| [getShowSearch()](#getShowSearch--) | Показать/скрыть раздел поиска. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Показать/скрыть раздел поиска. |
| [getShowTopPane()](#getShowTopPane--) | Показать/скрыть всю верхнюю панель. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Показать/скрыть всю верхнюю панель. |
| [getShowBottomPane()](#getShowBottomPane--) | Показать/скрыть нижнюю панель. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Показать/скрыть нижнюю панель. |
| [getShowLeftPane()](#getShowLeftPane--) | Показать/скрыть левую панель. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Показать/скрыть левую панель. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Открыть левую панель при запуске. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Открыть левую панель при запуске. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Включить/отключить контекстное меню. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Включить/отключить контекстное меню. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Изображение, которое будет отображаться в качестве логотипа в правом верхнем углу просмотрщика. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Изображение, которое будет отображаться в качестве логотипа в правом верхнем углу просмотрщика. |
| [getLogoLink()](#getLogoLink--) | Получает или задает полный адрес гиперссылки для логотипа. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Получает или задает полный адрес гиперссылки для логотипа. |
| [getJpegQuality()](#getJpegQuality--) | Указывает качество JPEG-изображений. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Указывает качество JPEG-изображений. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

Указывает, следует ли сжимать сгенерированный документ SWF или нет. Значение по умолчанию - true.

**Возвращаемое значение:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

Указывает, следует ли сжимать сгенерированный документ SWF или нет. Значение по умолчанию - true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

Указывает, следует ли включать в сгенерированный документ SWF интегрированный просмотрщик документов или нет. Значение по умолчанию - true.

**Возвращаемое значение:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

Указывает, следует ли включать в сгенерированный документ SWF интегрированный просмотрщик документов или нет. Значение по умолчанию - true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

Указывает, следует ли отображать границу вокруг страниц. Значение по умолчанию - true.

**Возвращаемое значение:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

Указывает, следует ли отображать границу вокруг страниц. Значение по умолчанию - true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Указывает, следует ли включать скрытые слайды в сгенерированный документ или нет. Значение по умолчанию - false.

**Возвращаемое значение:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать скрытые слайды в сгенерированный документ или нет. Значение по умолчанию - false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

Показать/скрыть кнопку полноэкранного режима. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Возвращаемое значение:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

Показать/скрыть кнопку полноэкранного режима. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

Показать/скрыть переключатель страниц. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Возвращаемое значение:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

Показать/скрыть переключатель страниц. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

Показать/скрыть раздел поиска. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Возвращаемое значение:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

Показать/скрыть раздел поиска. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

Показать/скрыть всю верхнюю панель. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Возвращаемое значение:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

Показать/скрыть всю верхнюю панель. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

Показать/скрыть нижнюю панель. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Возвращаемое значение:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

Показать/скрыть нижнюю панель. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

Показать/скрыть левую панель. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Возвращаемое значение:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

Показать/скрыть левую панель. Может быть переопределено во flashvars. Значение по умолчанию - true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

Открыть левую панель при запуске. Может быть переопределено во flashvars. Значение по умолчанию - false.

**Возвращаемое значение:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

Открыть левую панель при запуске. Может быть переопределено во flashvars. Значение по умолчанию - false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

Включить/отключить контекстное меню. Значение по умолчанию - true.

**Возвращаемое значение:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

Включить/отключить контекстное меню. Значение по умолчанию - true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

Изображение, которое будет отображаться в качестве логотипа в правом верхнем углу просмотрщика. Изображение должно быть PNG размером 32×64 пикселей, иначе логотип может отображаться некорректно.

**Возвращаемое значение:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

Изображение, которое будет отображаться в качестве логотипа в правом верхнем углу просмотрщика. Изображение должно быть PNG размером 32×64 пикселей, иначе логотип может отображаться некорректно.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

Получает или задает полный адрес гиперссылки для логотипа. Имеет эффект только если указан (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Возвращаемое значение:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

Получает или задает полный адрес гиперссылки для логотипа. Имеет эффект только если указан (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Указывает качество JPEG-изображений. Значение по умолчанию - 95.

**Возвращаемое значение:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Указывает качество JPEG-изображений. Значение по умолчанию - 95.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Это свойство не поддерживает назначение объектов типа [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Это свойство не поддерживает назначение объектов типа [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
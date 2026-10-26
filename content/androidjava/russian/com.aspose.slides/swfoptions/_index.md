---
title: SwfOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате Swf.
type: docs
url: /ru/com.aspose.slides/swfoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Все реализованные интерфейсы:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Предоставляет параметры, контролирующие, как презентация сохраняется в формате Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Создайте объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Сохранение презентации и страниц заметок
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Конструктор по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в сгенерированный документ. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в сгенерированный документ. |
| [getCompressed()](#getCompressed--) | Указывает, следует ли сжимать сгенерированный документ SWF. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Указывает, следует ли сжимать сгенерированный документ SWF. |
| [getViewerIncluded()](#getViewerIncluded--) | Указывает, следует ли включать интегрированный просмотрщик документов в сгенерированный документ SWF. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Указывает, следует ли включать интегрированный просмотрщик документов в сгенерированный документ SWF. |
| [getShowPageBorder()](#getShowPageBorder--) | Указывает, следует ли показывать границу вокруг страниц. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Указывает, следует ли показывать границу вокруг страниц. |
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
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Начинать с открытой левой панелью. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Начинать с открытой левой панелью. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Включить/отключить контекстное меню. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Включить/отключить контекстное меню. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Изображение, которое будет отображаться в виде логотипа в правом верхнем углу просмотрщика. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Изображение, которое будет отображаться в виде логотипа в правом верхнем углу просмотрщика. |
| [getLogoLink()](#getLogoLink--) | Получает или задает полный URL-адрес гиперссылки для логотипа. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Получает или задает полный URL-адрес гиперссылки для логотипа. |
| [getJpegQuality()](#getJpegQuality--) | Указывает качество JPEG-изображений. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Указывает качество JPEG-изображений. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Конструктор по умолчанию.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Указывает, следует ли включать скрытые слайды в сгенерированный документ. По умолчанию false.

**Возвращаемое значение:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать скрытые слайды в сгенерированный документ. По умолчанию false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Указывает, следует ли сжимать сгенерированный документ SWF. По умолчанию true.

**Возвращаемое значение:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Указывает, следует ли сжимать сгенерированный документ SWF. По умолчанию true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Указывает, следует ли включать интегрированный просмотрщик документов в сгенерированный документ SWF. По умолчанию true.

**Возвращаемое значение:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Указывает, следует ли включать интегрированный просмотрщик документов в сгенерированный документ SWF. По умолчанию true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Указывает, следует ли показывать границу вокруг страниц. По умолчанию true.

**Возвращаемое значение:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Указывает, следует ли показывать границу вокруг страниц. По умолчанию true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Показать/скрыть кнопку полноэкранного режима. Может быть переопределено через flashvars. По умолчанию true.

**Возвращаемое значение:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Показать/скрыть кнопку полноэкранного режима. Может быть переопределено через flashvars. По умолчанию true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Показать/скрыть переключатель страниц. Может быть переопределено через flashvars. По умолчанию true.

**Возвращаемое значение:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Показать/скрыть переключатель страниц. Может быть переопределено через flashvars. По умолчанию true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Показать/скрыть раздел поиска. Может быть переопределено через flashvars. По умолчанию true.

**Возвращаемое значение:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Показать/скрыть раздел поиска. Может быть переопределено через flashvars. По умолчанию true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Показать/скрыть всю верхнюю панель. Может быть переопределено через flashvars. По умолчанию true.

**Возвращаемое значение:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Показать/скрыть всю верхнюю панель. Может быть переопределено через flashvars. По умолчанию true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Показать/скрыть нижнюю панель. Может быть переопределено через flashvars. По умолчанию true.

**Возвращаемое значение:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Показать/скрыть нижнюю панель. Может быть переопределено через flashvars. По умолчанию true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Показать/скрыть левую панель. Может быть переопределено через flashvars. По умолчанию true.

**Возвращаемое значение:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Показать/скрыть левую панель. Может быть переопределено через flashvars. По умолчанию true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Начинать с открытой левой панелью. Может быть переопределено через flashvars. По умолчанию false.

**Возвращаемое значение:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Начинать с открытой левой панелью. Может быть переопределено через flashvars. По умолчанию false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Включить/отключить контекстное меню. По умолчанию true.

**Возвращаемое значение:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Включить/отключить контекстное меню. По умолчанию true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Изображение, которое будет отображаться в виде логотипа в правом верхнем углу просмотрщика. Изображение должно быть PNG размером 32x64 пикселя, иначе логотип может отображаться неверно.

**Возвращаемое значение:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Изображение, которое будет отображаться в виде логотипа в правом верхнем углу просмотрщика. Изображение должно быть PNG размером 32x64 пикселя, иначе логотип может отображаться неверно.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Получает или задает полный URL-адрес гиперссылки для логотипа. Имеет эффект только если указан (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Возвращаемое значение:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Получает или задает полный URL-адрес гиперссылки для логотипа. Имеет эффект только если указан (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Указывает качество JPEG-изображений. По умолчанию 95.

**Возвращаемое значение:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Указывает качество JPEG-изображений. По умолчанию 95.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Это свойство не поддерживает назначение объектов типа [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Это свойство не поддерживает назначение объектов типа [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

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
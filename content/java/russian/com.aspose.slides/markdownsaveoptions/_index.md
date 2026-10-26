---
title: MarkdownSaveOptions
second_title: Справочник API Aspose.Slides для Java
description: Представляет параметры, которые управляют тем, как презентация сохраняется в markdown.
type: docs
url: /ru/com.aspose.slides/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Представляет параметры, которые управляют тем, как презентация сохраняется в markdown.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [getExportType()](#getExportType--) | Указывает спецификацию markdown для преобразования презентации. |
| [setExportType(int value)](#setExportType-int-) | Указывает спецификацию markdown для преобразования презентации. |
| [getBasePath()](#getBasePath--) | Указывает базовый путь, где будет сохранён документ с ресурсами. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Указывает базовый путь, где будет сохранён документ с ресурсами. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Указывает имя папки для сохранения изображений. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Указывает имя папки для сохранения изображений. |
| [getNewLineType()](#getNewLineType--) | Указывает, должны ли новые строки в генерируемом документе быть \\r (Macintosh), \\n (Unix) или \\r\\n (Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Указывает, должны ли новые строки в генерируемом документе быть \\r (Macintosh), \\n (Unix) или \\r\\n (Windows). |
| [getShowComments()](#getShowComments--) | Указывает, следует ли отображать комментарии в генерируемом документе. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Указывает, следует ли отображать комментарии в генерируемом документе. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в генерируемый документ. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в генерируемый документ. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Указывает, следует ли показывать номер каждого слайда в генерируемом документе. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Указывает, следует ли показывать номер каждого слайда в генерируемом документе. |
| [getFlavor()](#getFlavor--) | Указывает спецификацию markdown для преобразования презентации. |
| [setFlavor(int value)](#setFlavor-int-) | Указывает спецификацию markdown для преобразования презентации. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Получает или задаёт строку формата, используемую для заголовков номеров слайдов в выводе Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Получает или задаёт строку формата, используемую для заголовков номеров слайдов в выводе Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Указывает, как следует обрабатывать повторяющиеся обычные пробельные символы при экспорте в Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Указывает, как следует обрабатывать повторяющиеся обычные пробельные символы при экспорте в Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Если установлено в true, удаляет пустые строки или строки, содержащие только пробелы, из окончательного вывода Markdown. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Если установлено в true, удаляет пустые строки или строки, содержащие только пробелы, из окончательного вывода Markdown. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Событие возникает для каждого не-SVG изображения (bitmap или metafile) во время экспорта в Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Событие возникает для каждого SVG-изображения во время экспорта в Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Конструктор.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Указывает спецификацию markdown для преобразования презентации. По умолчанию — TextOnly.

**Возвращаемое значение:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Указывает спецификацию markdown для преобразования презентации. По умолчанию — TextOnly.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Указывает базовый путь, где будет сохранён документ с ресурсами. По умолчанию — текущий каталог приложения.

**Возвращаемое значение:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Указывает базовый путь, где будет сохранён документ с ресурсами. По умолчанию — текущий каталог приложения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Указывает имя папки для сохранения изображений. По умолчанию — Images.

**Возвращаемое значение:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Указывает имя папки для сохранения изображений. По умолчанию — Images.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Указывает, должны ли новые строки в генерируемом документе быть \\r (Macintosh), \\n (Unix) или \\r\\n (Windows). По умолчанию — Unix.

**Возвращаемое значение:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Указывает, должны ли новые строки в генерируемом документе быть \\r (Macintosh), \\n (Unix) или \\r\\n (Windows). По умолчанию — Unix.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Указывает, следует ли отображать комментарии в генерируемом документе. По умолчанию — false.

**Возвращаемое значение:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Указывает, следует ли отображать комментарии в генерируемом документе. По умолчанию — false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Указывает, следует ли включать скрытые слайды в генерируемый документ. По умолчанию — false.

**Возвращаемое значение:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать скрытые слайды в генерируемый документ. По умолчанию — false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Указывает, следует ли показывать номер каждого слайда в генерируемом документе. По умолчанию — false.

**Возвращаемое значение:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Указывает, следует ли показывать номер каждого слайда в генерируемом документе. По умолчанию — false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Указывает спецификацию markdown для преобразования презентации. По умолчанию — Multi-markdown.

**Возвращаемое значение:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Указывает спецификацию markdown для преобразования презентации. По умолчанию — Multi-markdown.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Получает или задаёт строку формата, используемую для заголовков номеров слайдов в выводе Markdown. Формат должен включать плейсхолдер "\{0\}", который будет заменён индексом слайда во время экспорта. Пример: "\# Slide \{0\}" даст "\# Slide 1", "\# Slide 2" и т.д.

**Возвращаемое значение:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Получает или задаёт строку формата, используемую для заголовков номеров слайдов в выводе Markdown. Формат должен включать плейсхолдер "\{0\}", который будет заменён индексом слайда во время экспорта. Пример: "\# Slide \{0\}" даст "\# Slide 1", "\# Slide 2" и т.д.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Указывает, как следует обрабатывать повторяющиеся обычные пробельные символы при экспорте в Markdown. Это свойство определяет, будут ли последовательные пробелы: - сохраняться как обычные пробелы, - чередоваться между обычными пробелами и неразрывными пробелами (�), - либо полностью заменяться (после первого) неразрывным пробелом для сохранения визуального выравнивания в выводе Markdown. Значение по умолчанию — [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Возвращаемое значение:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Указывает, как следует обрабатывать повторяющиеся обычные пробельные символы при экспорте в Markdown. Это свойство определяет, будут ли последовательные пробелы: - сохраняться как обычные пробелы, - чередоваться между обычными пробелами и неразрывными пробелами (�), - либо полностью заменяться (после первого) неразрывным пробелом для сохранения визуального выравнивания в выводе Markdown. Значение по умолчанию — [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Если установлено в true, удаляет пустые строки или строки, содержащие только пробелы, из окончательного вывода Markdown. По умолчанию — false.

**Возвращаемое значение:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Если установлено в true, удаляет пустые строки или строки, содержащие только пробелы, из окончательного вывода Markdown. По умолчанию — false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Событие возникает для каждого не-SVG изображения (bitmap или metafile) во время экспорта в Markdown. Позволяет настроить способ сохранения изображения и формирование ссылки. Если событие не обработано, изображение сохраняется локально с относительной ссылкой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Событие сохранения изображения Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Событие возникает для каждого SVG-изображения во время экспорта в Markdown. Позволяет переопределить стандартный способ сохранения и генерацию ссылки. Если событие не обработано, SVG сохраняется локально с относительной ссылкой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Событие сохранения SVG-изображения Markdown. |
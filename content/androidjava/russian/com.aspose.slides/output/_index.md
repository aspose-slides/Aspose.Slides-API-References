---
title: Output
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет коллекцию выходных элементов для IWebDocument.
type: docs
url: /ru/com.aspose.slides/output/
---
**Наследование:**  
java.lang.Object  
```
public final class Output
```

Представляет коллекцию выходных элементов для IWebDocument.

## Методы

| Метод | Описание |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Добавляет выходной элемент для объекта контекста. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Добавляет выходной элемент для изображения. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Добавляет выходной элемент для изображения. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Добавляет выходной элемент для видео. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Создаёт и добавляет элемент выходного файла для указанного шрифта. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Добавляет выходной элемент для текстового содержимого. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Привязывает ресурс к выходному файлу. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Возвращает путь для данного ресурса. |

### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Добавляет выходной элемент для объекта контекста.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь вывода. |
| templateKey | java.lang.String | Ключ шаблона, используемый для преобразования объекта контекста перед выводом. |
| contextObject | TContextObject | Объект контекста. |

**Возвращаемое значение:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) объект для объекта контекста.

### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Добавляет выходной элемент для изображения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь вывода. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Изображение для вывода. |

**Возвращаемое значение:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) объект для изображения.

### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Добавляет выходной элемент для изображения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь вывода. |
| image | [IImage](../../com.aspose.slides/iimage) | Изображение для вывода. |

**Возвращаемое значение:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) объект для изображения.

### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Добавляет выходной элемент для видео.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь вывода. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Видео для вывода. |

**Возвращаемое значение:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) объект для видео.

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Создаёт и добавляет элемент выходного файла для указанного шрифта.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь к файлу, куда будет сохранён вывод шрифта. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Данные шрифта, которые будут записаны в вывод. |
| fontStyle | int | Стиль шрифта (например, Regular, Bold, Italic). |

**Возвращаемое значение:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Экземпляр [IOutputFile](../../com.aspose.slides/ioutputfile) для сгенерированного шрифта.

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Добавляет выходной элемент для текстового содержимого.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь вывода. |
| textContent | java.lang.String | Содержимое для вывода. |

**Возвращаемое значение:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) объект для текстового содержимого.

### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Привязывает ресурс к выходному файлу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Выходной файл. |
| obj | java.lang.Object | Объект ресурса. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

Возвращает путь для данного ресурса.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект ресурса. |

**Возвращаемое значение:**
java.lang.String - Путь к ресурсу.
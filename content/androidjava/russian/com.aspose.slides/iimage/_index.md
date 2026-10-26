---
title: IImage
second_title: Справочник API Aspose.Slides для Android через Java
description: Представляет растровое или векторное изображение.
type: docs
url: /ru/com.aspose.slides/iimage/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Представляет растровое или векторное изображение.

--------------------

Этот интерфейс предоставляет общую абстракцию для работы как с растровыми, так и с векторными изображениями. Реализации могут различаться в зависимости от типа базового изображения.
## Методы

| Метод | Описание |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Сохраняет изображение в файл. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Сохраняет изображение в файл в указанном формате. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Сохраняет изображение в поток в указанном формате. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Сохраняет изображение в файл в указанном формате и качестве. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Сохраняет изображение в поток в указанном формате и качестве. |
| [getSize()](#getSize--) | Получает размер изображения. |
| [getWidth()](#getWidth--) | Получает ширину изображения в пикселях. |
| [getHeight()](#getHeight--) | Получает высоту изображения в пикселях. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Сохраняет изображение в файл.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Путь к файлу, в который будет сохранено изображение. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Сохраняет изображение в файл в указанном формате.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Путь к файлу, в который будет сохранено изображение. |
| format | int | Формат изображения. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Сохраняет изображение в поток в указанном формате.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который будет сохранено изображение. |
| format | int | Формат изображения. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Сохраняет изображение в файл в указанном формате и качестве.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Путь к файлу, в который будет сохранено изображение. |
| format | int | Формат изображения. |
| quality | int | Качество сохраняемого изображения (от 0 до 100). Этот параметр влияет только на сохранение в [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); для всех остальных форматов он игнорируется. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Сохраняет изображение в поток в указанном формате и качестве.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который будет сохранено изображение. |
| format | int | Формат изображения. |
| quality | int | Качество сохраняемого изображения (от 0 до 100). Этот параметр влияет только на сохранение в [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); для всех остальных форматов он игнорируется. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Получает размер изображения.

**Возвращаемое значение:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Получает ширину изображения в пикселях.

**Возвращаемое значение:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Получает высоту изображения в пикселях.

**Возвращаемое значение:**
int
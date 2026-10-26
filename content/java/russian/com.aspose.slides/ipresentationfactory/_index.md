---
title: IPresentationFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create presentation via COM interface
type: docs
url: /ru/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Позволяет создавать презентацию через COM-интерфейс
## Методы

| Метод | Описание |
| --- | --- |
| [createPresentation()](#createPresentation--) | Creates new presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Creates new presentation with additional load options |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Gets info about presentation in specified file. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Gets info about presentation in specified stream. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Reads an existing presentation from array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Reads an existing presentation from array with additional load options |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Reads an existing presentation from stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Reads an existing presentation from file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Retrieves the raw text from the slides |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```


Создает новую презентацию.

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Новая презентация
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```


Создает новую презентацию с дополнительными параметрами загрузки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Параметры загрузки |

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Новая презентация
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```


Получает информацию о презентации в указанном файле.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Файл презентации. |

**Возвращаемое значение:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Информация о презентации
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```


Получает информацию о презентации в указанном потоке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток презентации. |

**Возвращаемое значение:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Информация о презентации.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```


Читает существующую презентацию из массива

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | Массив для чтения |

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Прочитанная презентация
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Читает существующую презентацию из массива с дополнительными параметрами загрузки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | Массив для чтения |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Параметры загрузки |

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Прочитанная презентация
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```


Читает существующую презентацию из потока

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток для чтения |

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Прочитанная презентация
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Читает существующую презентацию из потока с дополнительными параметрами загрузки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток для чтения |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Параметры загрузки |

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Прочитанная презентация
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```


Читает существующую презентацию из файла

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Имя файла |

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Прочитанная презентация
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```


Читает существующую презентацию из потока с дополнительными параметрами загрузки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Имя файла |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Параметры загрузки |

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Прочитанная презентация
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```


Получает исходный текст со слайдов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Входной файл |
| mode | int | Режим извлечения |

**Возвращаемое значение:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Экземпляр PresentationText, содержащий массив SlideText, представляющий исходный текст слайдов
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```


Получает исходный текст со слайдов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток |
| mode | int | Режим извлечения |

**Возвращаемое значение:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Экземпляр PresentationText, содержащий массив SlideText, представляющий исходный текст слайдов
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Получает исходный текст со слайдов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток |
| mode | int | Режим извлечения |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Параметры загрузки |

**Возвращаемое значение:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Экземпляр PresentationText, содержащий массив SlideText, представляющий исходный текст слайдов
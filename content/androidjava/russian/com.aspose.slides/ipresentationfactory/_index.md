---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Reference
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
| [createPresentation()](#createPresentation--) | Создает новую презентацию. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Создает новую презентацию с дополнительными параметрами загрузки |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Получает информацию о презентации в указанном файле. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Получает информацию о презентации в указанном потоке. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Читает существующую презентацию из массива |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Читает существующую презентацию из массива с дополнительными параметрами загрузки |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Читает существующую презентацию из потока |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Читает существующую презентацию из потока с дополнительными параметрами загрузки |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Читает существующую презентацию из файла |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Читает существующую презентацию из потока с дополнительными параметрами загрузки |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Извлекает необработанный текст со слайдов |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Извлекает необработанный текст со слайдов |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Извлекает необработанный текст со слайдов |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Имя файла |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Параметры загрузки |

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Прочитанная презентация
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```


Извлекает необработанный текст со слайдов

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Входной файл |
| mode | int | Режим извлечения |

**Возвращаемое значение:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Экземпляр PresentationText, содержащий массив SlideText, представляющий необработанный текст слайдов
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```


Извлекает необработанный текст со слайдов

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток |
| mode | int | Режим извлечения |

**Возвращаемое значение:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Экземпляр PresentationText, содержащий массив SlideText, представляющий необработанный текст слайдов
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Извлекает необработанный текст со слайдов

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток |
| mode | int | Режим извлечения |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Параметры загрузки |

**Возвращаемое значение:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Экземпляр PresentationText, содержащий массив SlideText, представляющий необработанный текст слайдов
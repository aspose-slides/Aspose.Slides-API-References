---
title: PresentationFactory
second_title: Справочник API Aspose.Slides для Java
description: Позволяет создавать презентацию через COM-интерфейс
type: docs
url: /ru/com.aspose.slides/presentationfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Позволяет создавать презентацию через COM-интерфейс

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getInstance()](#getInstance--) | Статический экземпляр фабрики презентаций. |
| [createPresentation()](#createPresentation--) | Создает новую презентацию. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Создает новую презентацию с дополнительными параметрами загрузки |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Создает новый объект PresentationInfo из файла и привязывает к нему презентацию. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Создает новый объект PresentationInfo из потока и привязывает к нему презентацию. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Читает существующую презентацию из массива |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Читает существующую презентацию из массива с дополнительными параметрами загрузки |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Читает существующую презентацию из потока |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Читает существующую презентацию из потока с дополнительными параметрами загрузки |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Читает существующую презентацию из файла |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Читает существующую презентацию из потока с дополнительными параметрами загрузки |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Извлекает необработанный текст со слайдов |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Извлекает необработанный текст со слайдов |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Извлекает необработанный текст со слайдов |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


Статический экземпляр фабрики презентаций. Только для чтения [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Возвращаемое значение:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


Создает новую презентацию.

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Новая презентация
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
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
public final IPresentationInfo getPresentationInfo(String file)
```


Создает новый объект PresentationInfo из файла и привязывает к нему презентацию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Файл презентации. |

**Возвращаемое значение:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Информация о презентации, привязанная к презентации.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


Создает новый объект PresentationInfo из потока и привязывает к нему презентацию. Получает информацию о презентации из указанного потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток презентации. |

**Возвращаемое значение:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Информация о презентации, привязанная к презентации.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
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
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
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
public final IPresentation readPresentation(InputStream stream)
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
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
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
public final IPresentation readPresentation(String file)
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
public final IPresentation readPresentation(String file, ILoadOptions options)
```


Читает существующую презентацию из файла с дополнительными параметрами загрузки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Имя файла |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Параметры загрузки |

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation) - Прочитанная презентация
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


Извлекает необработанный текст со слайдов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Входной файл |
| mode | int | Режим извлечения |

**Возвращаемое значение:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Экземпляр PresentationText, содержащий массив SlideText, представляющий необработанный текст слайдов
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


Извлекает необработанный текст со слайдов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток |
| mode | int | Режим извлечения |

**Возвращаемое значение:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Экземпляр PresentationText, содержащий массив SlideText, представляющий необработанный текст слайдов
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Извлекает необработанный текст со слайдов

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток |
| mode | int | Режим извлечения |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Параметры загрузки |

**Возвращаемое значение:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Экземпляр PresentationText, содержащий массив SlideText, представляющий необработанный текст слайдов
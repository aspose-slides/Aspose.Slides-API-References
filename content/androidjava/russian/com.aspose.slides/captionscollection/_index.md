---
title: CaptionsCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию закрытых субтитров.
type: docs
url: /ru/com.aspose.slides/captionscollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Представляет коллекцию закрытых субтитров.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает закрытые субтитры по указанному индексу. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Добавляет закрытые субтитры WebVTT в конец коллекции. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Добавляет закрытые субтитры WebVTT в конец коллекции из потока. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Удаляет указанные закрытые субтитры из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет закрытые субтитры по указанному индексу. |
| [clear()](#clear--) | Удаляет все закрытые субтитры из коллекции. |
| [getCount()](#getCount--) | Возвращает количество элементов в коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по элементам коллекции. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


Возвращает закрытые субтитры по указанному индексу. Только для чтения [ICaptions](../../com.aspose.slides/icaptions).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```


Добавляет закрытые субтитры WebVTT в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| label | java.lang.String | Метка закрытых субтитров. |
| filePath | java.lang.String | Путь к файлу WebVTT. |

**Возвращаемое значение:**
[ICaptions](../../com.aspose.slides/icaptions) - Экземпляр добавленного [ICaptions](../../com.aspose.slides/icaptions).
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```


Добавляет закрытые субтитры WebVTT в конец коллекции из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| label | java.lang.String | Метка закрытых субтитров. |
| stream | java.io.InputStream | Входной поток, содержащий данные в формате WebVTT. |

**Возвращаемое значение:**
[ICaptions](../../com.aspose.slides/icaptions) - Экземпляр добавленного [ICaptions](../../com.aspose.slides/icaptions).
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


Удаляет указанные закрытые субтитры из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Закрытые субтитры для удаления. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Удаляет закрытые субтитры по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс удаляемых закрытых субтитров. |

### clear() {#clear--}
```
public final void clear()
```


Удаляет все закрытые субтитры из коллекции.

### getCount() {#getCount--}
```
public final int getCount()
```


Возвращает количество элементов в коллекции. Только для чтения  int .

**Возвращаемое значение:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


Возвращает перечислитель, который проходит по элементам коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> -  System.Collections.Generic.IEnumerator1  который можно использовать для перебора элементов коллекции.
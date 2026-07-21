---
title: ReadValueChunk()
second_title: Aspose.Slides для C++ справочник API
description: Читает большие потоки текста, вложенные в XML-документ.
type: docs
weight: 807
url: /ru/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) метод


Читает большие потоки текста, вложенные в XML-документ.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Массив символов, который служит буфером, в который записывается содержимое текста. Это значение не может быть **nullptr**. |
| index | **int32_t** | Смещение в буфере, с которого [XmlReader](../) может начать копировать результаты. |
| count | **int32_t** | Максимальное количество символов, которое можно скопировать в буфер. Фактическое количество скопированных символов возвращается этим методом. |

### Возвращаемое значение

Количество символов, считанных в буфер. Ноль возвращается, когда больше нет текстового содержимого.

## См. также

* Определение типа [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)
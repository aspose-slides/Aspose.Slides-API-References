---
title: idx_get()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе возвращает значение атрибута с указанным индексом.
type: docs
weight: 612
url: /ru/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) метод


Если переопределён в производном классе, возвращает значение атрибута с указанным индексом.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| i | **int32_t** | Индекс атрибута. |

### Значение возврата

Значение указанного атрибута.

## XmlReader::idx_get(String) метод


Если переопределён в производном классе, возвращает значение атрибута с указанным [XmlReader::get_Name](../get_name/) значением.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя атрибута. |

### Значение возврата

Значение указанного атрибута. Если атрибут не найден, возвращается **nullptr**.

## XmlReader::idx_get(String, String) метод


Если переопределён в производном классе, возвращает значение атрибута с указанными [XmlReader::get_LocalName](../get_localname/) и [XmlReader::get_NamespaceURI](../get_namespaceuri/) значениями.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Локальное имя атрибута. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён атрибута. |

### Значение возврата

Значение указанного атрибута. Если атрибут не найден, возвращается **nullptr**.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)
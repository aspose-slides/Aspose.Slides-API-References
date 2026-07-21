---
title: MoveToAttribute()
second_title: Справочник API Aspose.Slides для C++
description: "При переопределении в производном классе перемещается к атрибуту с указанным значением XmlReader::get_Name."
type: docs
weight: 625
url: /ru/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) метод

Когда переопределяется в производном классе, перемещается к атрибуту с указанным [XmlReader::get_Name](../get_name/) значением.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Полное имя атрибута. |

### Возвращаемое значение

**true** если атрибут найден; иначе **false**. Если **false**, позиция читателя не изменяется.

## XmlReader::MoveToAttribute(String, String) метод

Когда переопределяется в производном классе, перемещается к атрибуту с указанными [XmlReader::get_LocalName](../get_localname/) и [XmlReader::get_NamespaceURI](../get_namespaceuri/) значениями.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Локальное имя атрибута. |
| ns | [String](../../../system/string/) | URI пространства имён атрибута. |

### Возвращаемое значение

**true** если атрибут найден; иначе **false**. Если **false**, позиция читателя не изменяется.

## XmlReader::MoveToAttribute(int32_t) метод

Когда переопределяется в производном классе, перемещается к атрибуту с указанным индексом.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | Индекс атрибута. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)
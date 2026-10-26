---
title: RemoveParam()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет параметр из XsltArgumentList.
type: docs
weight: 66
url: /ru/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) метод

Удаляет параметр из [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Имя параметра, который необходимо удалить. [XsltArgumentList](../) не проверяет, является ли переданное имя допустимым локальным именем; однако имя не может быть **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | URI пространства имён параметра, который необходимо удалить. |

### Возвращаемое значение

Объект параметра или **nullptr**, если он не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [String](../../../system/string/)
* Класс [XsltArgumentList](../)
* Пространство имён [System::Xml::Xsl](../../)
* Библиотека [Aspose.Slides](../../../)
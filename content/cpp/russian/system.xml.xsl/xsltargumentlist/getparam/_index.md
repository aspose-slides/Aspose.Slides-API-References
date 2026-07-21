---
title: GetParam()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает параметр, связанный с квалифицированным именем пространства имен.
type: docs
weight: 14
url: /ru/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) method

Возвращает параметр, связанный с квалифицированным именем пространства имен.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Имя параметра. [XsltArgumentList](../) не проверяет, что переданное имя является допустимым локальным именем; однако имя не может быть **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | URI пространства имен, связанный с параметром. |

### Возвращаемое значение

Объект параметра или **nullptr**, если он не найден.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [String](../../../system/string/)
* Класс [XsltArgumentList](../)
* Пространство имён [System::Xml::Xsl](../../)
* Библиотека [Aspose.Slides](../../../)
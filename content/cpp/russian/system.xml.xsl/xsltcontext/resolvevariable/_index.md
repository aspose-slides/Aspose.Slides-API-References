---
title: ResolveVariable()
second_title: Aspose.Slides для C++ справочник API
description: При переопределении в производном классе разрешает ссылку на переменную и возвращает объект IXsltContextVariable, представляющий переменную.
type: docs
weight: 14
url: /ru/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) метод

При переопределении в производном классе разрешает ссылку на переменную и возвращает [IXsltContextVariable](../../ixsltcontextvariable/), представляющий переменную.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Префикс переменной в том виде, в котором он появляется в выражении [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Имя переменной. |

### Возвращаемое значение

Объект [IXsltContextVariable](../../ixsltcontextvariable/), представляющий переменную во время выполнения.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IXsltContextVariable](../../ixsltcontextvariable/)
* Класс [String](../../../system/string/)
* Класс [XsltContext](../)
* Пространство имён [System::Xml::Xsl](../../)
* Библиотека [Aspose.Slides](../../../)
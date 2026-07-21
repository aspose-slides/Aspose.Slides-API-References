---
title: Evaluate()
second_title: Справочник API Aspose.Slides для C++
description: Оценивает переменную во время выполнения и возвращает объект, представляющий значение переменной.
type: docs
weight: 40
url: /ru/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) метод

Оценивает переменную во время выполнения и возвращает объект, представляющий значение переменной.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Объект [XsltContext](../../xsltcontext/), представляющий контекст выполнения переменной. |

### Возвращаемое значение

Объект [Object](../../../system/object/), представляющий значение переменной. Возможные типы возвращаемого значения включают number, string, [Boolean](../../../system/boolean/), фрагмент документа или набор узлов.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [XsltContext](../../xsltcontext/)
* Класс [IXsltContextVariable](../)
* Пространство имён [System::Xml::Xsl](../../)
* Библиотека [Aspose.Slides](../../../)
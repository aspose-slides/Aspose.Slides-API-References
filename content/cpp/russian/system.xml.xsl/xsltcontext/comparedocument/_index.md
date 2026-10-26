---
title: CompareDocument()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе сравнивает базовые униформные идентификаторы ресурсов (URI) двух документов, основываясь на порядке их загрузки процессором XSLT (то есть классом XslTransform).
type: docs
weight: 53
url: /ru/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) метод


При переопределении в производном классе сравнивает базовые униформные идентификаторы ресурсов (URI) двух документов, исходя из порядка их загрузки процессором XSLT (то есть класса [XslTransform](../../xsltransform/)).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | Базовый URI первого документа для сравнения. |
| nextbaseUri | [String](../../../system/string/) | Базовый URI второго документа для сравнения. |

### Возвращаемое значение

Целочисленное значение, описывающее относительный порядок двух базовых URI: -1, если **baseUri** появляется до **nextbaseUri**; 0, если два базовых URI идентичны; и 1, если **baseUri** появляется после **nextbaseUri**.

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [XsltContext](../)
* Пространство имён [System::Xml::Xsl](../../)
* Библиотека [Aspose.Slides](../../../)
---
title: Evaluate()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет оценку указанного XPath-выражения и возвращает типизированный результат.
type: docs
weight: 807
url: /ru/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) метод


Выполняет оценку указанного [XPath](../../) выражения и возвращает типизированный результат.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Строка, представляющая [XPath](../../) выражение, которое может быть оценено. |

### Возвращаемое значение

Результат выражения ([Boolean](../../../system/boolean/), число, строка или набор узлов). Это соответствует объектам [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) или [XPathNodeIterator](../../xpathnodeiterator/) соответственно.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) метод


Выполняет оценку указанного [XPath](../../) выражения и возвращает типизированный результат, используя указанный объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) для разрешения префиксов пространств имён в [XPath](../../) выражении.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Строка, представляющая [XPath](../../) выражение, которое может быть оценено. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), используемый для разрешения префиксов пространств имён в [XPath](../../) выражении. |

### Возвращаемое значение

Результат выражения ([Boolean](../../../system/boolean/), число, строка или набор узлов). Это соответствует объектам [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) или [XPathNodeIterator](../../xpathnodeiterator/) соответственно.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) метод


Выполняет оценку [XPathExpression](../../xpathexpression/) и возвращает типизированный результат.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Объект [XPathExpression](../../xpathexpression/), который может быть оценен. |

### Возвращаемое значение

Результат выражения ([Boolean](../../../system/boolean/), число, строка или набор узлов). Это соответствует объектам [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) или [XPathNodeIterator](../../xpathnodeiterator/) соответственно.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) метод


Использует предоставленный контекст для оценки [XPathExpression](../../xpathexpression/) и возвращает типизированный результат.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Объект [XPathExpression](../../xpathexpression/), который может быть оценен. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Объект [XPathNodeIterator](../../xpathnodeiterator/), указывающий на выбранный набор узлов, над которым будет выполнена оценка. |

### Возвращаемое значение

Результат выражения ([Boolean](../../../system/boolean/), число, строка или набор узлов). Это соответствует объектам [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) или [XPathNodeIterator](../../xpathnodeiterator/) соответственно.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [String](../../../system/string/)
* Класс [XPathNavigator](../)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Класс [XPathExpression](../../xpathexpression/)
* Класс [XPathNodeIterator](../../xpathnodeiterator/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)
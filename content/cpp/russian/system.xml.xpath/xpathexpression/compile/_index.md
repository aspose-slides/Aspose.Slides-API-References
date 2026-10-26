---
title: Compile()
second_title: Aspose.Slides для C++ справочник API
description: Компилирует указанное XPath-выражение и возвращает объект XPathExpression, представляющий это XPath-выражение.
type: docs
weight: 66
url: /ru/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) метод

Компилирует указанное выражение [XPath](../../) и возвращает объект [XPathExpression](../), представляющий выражение [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Выражение [XPath](../../). |

### Возвращаемое значение

Объект [XPathExpression](../).

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) метод

Компилирует указанное выражение [XPath](../../), используя объект [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/), указанный для разрешения пространств имён, и возвращает объект [XPathExpression](../), представляющий выражение [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Выражение [XPath](../../). |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Объект, реализующий интерфейс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) для разрешения пространств имён. |

### Возвращаемое значение

Объект [XPathExpression](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XPathExpression](../)
* Класс [String](../../../system/string/)
* Класс [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Пространство имён [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
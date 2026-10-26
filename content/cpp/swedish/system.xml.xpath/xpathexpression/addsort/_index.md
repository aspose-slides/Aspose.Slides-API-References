---
title: AddSort()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass sorteras noderna som väljs av XPath-uttrycket enligt det specificerade IComparer-objektet.
type: docs
weight: 27
url: /sv/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) metod

När den åsidosätts i en avledd klass sorteras noderna som väljs av [XPath](../../)-uttrycket enligt det specificerade IComparer-objektet.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Ett objekt som representerar sorteringsnyckeln. Detta kan vara **string**-värdet för noden eller ett [XPathExpression](../)-objekt med ett kompilerat [XPath](../../)-uttryck. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Ett IComparer-objekt som tillhandahåller jämförelser av specifika datatyper för att jämföra två objekt för ekvivalens. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) metod


När den åsidosätts i en avledd klass sorteras noderna som väljs av [XPath](../../)-uttrycket enligt de angivna parametrarna.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Ett objekt som representerar sorteringsnyckeln. Detta kan vara **string**-värdet för noden eller ett [XPathExpression](../)-objekt med ett kompilerat [XPath](../../)-uttryck. |
| order | [XmlSortOrder](../../xmlsortorder/) | Ett XmlSortOrder-värde som anger sorteringsordningen. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Ett XmlCaseOrder-värde som anger hur versaler och gemener ska sorteras. |
| lang | [String](../../../system/string/) | Språket som ska användas för jämförelse. Använder klassen [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) som kan skickas till [String::Compare](../../../system/string/compare/)-metoden för språktyper, till exempel "us-en" för amerikansk engelska. Om en tom sträng anges används systemmiljön för att bestämma [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | Ett XmlDataType-värde som anger sorteringsordningen för datatypen. |

## Se även

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [IComparer](../../../system.collections.generic/icomparer/)
* Klass [XPathExpression](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
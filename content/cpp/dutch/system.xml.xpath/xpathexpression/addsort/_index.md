---
title: AddSort()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer deze in een afgeleide klasse wordt overschreven, sorteert het de knooppunten die door de XPath-expressie zijn geselecteerd volgens het opgegeven IComparer-object.
type: docs
weight: 27
url: /nl/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) methode


Wanneer deze in een afgeleide klasse wordt overschreven, sorteert het de knooppunten die door de [XPath](../../) expressie zijn geselecteerd volgens het opgegeven IComparer-object.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Een object dat de sorteersleutel vertegenwoordigt. Dit kan de **string**-waarde van het knooppunt zijn of een [XPathExpression](../) object met een gecompileerde [XPath](../../)-expressie. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Een IComparer-object dat de specifieke datatype-vergelijkingen biedt voor het vergelijken van twee objecten op gelijkheid. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) methode


Wanneer deze in een afgeleide klasse wordt overschreven, sorteert het de knooppunten die door de [XPath](../../) expressie zijn geselecteerd volgens de opgegeven parameters.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Een object dat de sorteersleutel vertegenwoordigt. Dit kan de **string**-waarde van het knooppunt zijn of een [XPathExpression](../) object met een gecompileerde [XPath](../../)-expressie. |
| order | [XmlSortOrder](../../xmlsortorder/) | Een XmlSortOrder-waarde die de sorteervolgorde aangeeft. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Een XmlCaseOrder-waarde die aangeeft hoe hoofdletters en kleine letters gesorteerd moeten worden. |
| lang | [String](../../../system/string/) | De taal die voor de vergelijking gebruikt moet worden. Maakt gebruik van de [Globalization::CultureInfo](../../../system.globalization/cultureinfo/)-klasse die kan worden doorgegeven aan de [String::Compare](../../../system/string/compare/)-methode voor de taaltypes, bijvoorbeeld "us-en" voor Amerikaans-Engels. Als een lege tekenreeks wordt opgegeven, wordt de systeem-omgeving gebruikt om de [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) te bepalen. |
| dataType | [XmlDataType](../../xmldatatype/) | Een XmlDataType-waarde die de sorteervolgorde voor het datatype aangeeft. |

## Zie ook

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [IComparer](../../../system.collections.generic/icomparer/)
* Klasse [XPathExpression](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
---
title: AddSort()
second_title: Aspose.Slides pro C++ API referenci
description: Když je přepsána v odvozené třídě, seřadí uzly vybrané výrazem XPath podle zadaného objektu IComparer.
type: docs
weight: 27
url: /cs/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) metoda


Když je přepsána v odvozené třídě, seřadí uzly vybrané výrazem [XPath](../../) podle zadaného objektu IComparer.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objekt představující klíč řazení. Může to být **string** hodnota uzlu nebo objekt [XPathExpression](../) s přeloženým výrazem [XPath](../../). |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Objekt IComparer, který poskytuje konkrétní porovnání datových typů pro porovnání dvou objektů na ekvivalenci. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) metoda


Když je přepsána v odvozené třídě, seřadí uzly vybrané výrazem [XPath](../../) podle dodaných parametrů.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objekt představující klíč řazení. Může to být **string** hodnota uzlu nebo objekt [XPathExpression](../) s přeloženým výrazem [XPath](../../). |
| order | [XmlSortOrder](../../xmlsortorder/) | Hodnota XmlSortOrder udávající pořadí řazení. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Hodnota XmlCaseOrder udávající, jak řadit velká a malá písmena. |
| lang | [String](../../../system/string/) | Jazyk použitý pro porovnání. Používá třídu [Globalization::CultureInfo](../../../system.globalization/cultureinfo/), kterou lze předat metodě [String::Compare](../../../system/string/compare/) pro typy jazyků, například „us-en“ pro americkou angličtinu. Pokud je zadán prázdný řetězec, systémové prostředí se použije k určení [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | Hodnota XmlDataType udávající pořadí řazení pro datový typ. |

## Viz také

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [IComparer](../../../system.collections.generic/icomparer/)
* Třída [XPathExpression](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
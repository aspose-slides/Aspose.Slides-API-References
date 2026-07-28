---
title: AddSort()
second_title: Aspose.Slides C++ API referencia
description: Ha egy származtatott osztályban felül van definiálva, a megadott IComparer objektum szerint rendezi a XPath kifejezés által kiválasztott csomópontokat.
type: docs
weight: 27
url: /hu/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) method


Ha egy származtatott osztályban felül van definiálva, a megadott IComparer objektum szerint rendezi a [XPath](../../) kifejezés által kiválasztott csomópontokat.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Egy objektum, amely a rendezési kulcsot képviseli. Lehet a csomópont **string** értéke vagy egy [XPathExpression](../) objektum, amely egy lefordított [XPath](../../) kifejezést tartalmaz. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Egy IComparer objektum, amely a specifikus adattípus-összehasonlításokat biztosít a két objektum ekvivalenciájának összehasonlításához. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) method


Ha egy származtatott osztályban felül van definiálva, a megadott paraméterek szerint rendezi a [XPath](../../) kifejezés által kiválasztott csomópontokat.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Egy objektum, amely a rendezési kulcsot képviseli. Lehet a csomópont **string** értéke vagy egy [XPathExpression](../) objektum, amely egy lefordított [XPath](../../) kifejezést tartalmaz. |
| order | [XmlSortOrder](../../xmlsortorder/) | Egy XmlSortOrder érték, amely a rendezési sorrendet jelzi. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Egy XmlCaseOrder érték, amely a nagy- és kisbetűk rendezésének módját jelzi. |
| lang | [String](../../../system/string/) | Az összehasonlításhoz használandó nyelv. A [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) osztályt használja, amely a [String::Compare](../../../system/string/compare/) metódusnak adható át a nyelvtípusokhoz, például az "us-en" az amerikai angolhoz. Ha egy üres karakterlánc van megadva, a rendszerkörnyezetet használja a [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) meghatározásához. |
| dataType | [XmlDataType](../../xmldatatype/) | Egy XmlDataType érték, amely az adattípus rendezési sorrendjét jelzi. |

## Lásd még

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [IComparer](../../../system.collections.generic/icomparer/)
* Osztály [XPathExpression](../)
* Osztály [String](../../../system/string/)
* Névterület [System::Xml::XPath](../../)
* Könyvtár [Aspose.Slides](../../../)
---
title: AddSort()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, sortiert die durch den XPath-Ausdruck ausgewählten Knoten gemäß dem angegebenen IComparer-Objekt.
type: docs
weight: 27
url: /de/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) Methode


Wenn in einer abgeleiteten Klasse überschrieben, sortiert die durch den [XPath](../../) Ausdruck ausgewählten Knoten gemäß dem angegebenen IComparer-Objekt.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Ein Objekt, das den Sortierschlüssel repräsentiert. Dies kann der **string**-Wert des Knotens sein oder ein [XPathExpression](../) Objekt mit einem kompilierten [XPath](../../) Ausdruck. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Ein IComparer-Objekt, das die spezifischen Datentypvergleiche für den Vergleich zweier Objekte auf Gleichwertigkeit bereitstellt. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) Methode


Wenn in einer abgeleiteten Klasse überschrieben, sortiert die durch den [XPath](../../) Ausdruck ausgewählten Knoten gemäß den übergebenen Parametern.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Ein Objekt, das den Sortierschlüssel repräsentiert. Dies kann der **string**-Wert des Knotens sein oder ein [XPathExpression](../) Objekt mit einem kompilierten [XPath](../../) Ausdruck. |
| order | [XmlSortOrder](../../xmlsortorder/) | Ein XmlSortOrder-Wert, der die Sortierreihenfolge angibt. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Ein XmlCaseOrder-Wert, der angibt, wie Groß- und Kleinbuchstaben sortiert werden. |
| lang | [String](../../../system/string/) | Die für den Vergleich zu verwendende Sprache. Verwendet die [Globalization::CultureInfo](../../../system.globalization/cultureinfo/)-Klasse, die dem [String::Compare](../../../system/string/compare/)-Methode für die Sprachtypen übergeben werden kann, zum Beispiel "us-en" für US-Englisch. Wenn ein leerer String angegeben wird, wird die Systemumgebung verwendet, um die [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) zu bestimmen. |
| dataType | [XmlDataType](../../xmldatatype/) | Ein XmlDataType-Wert, der die Sortierreihenfolge für den Datentyp angibt. |

## Siehe auch

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [XPathExpression](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
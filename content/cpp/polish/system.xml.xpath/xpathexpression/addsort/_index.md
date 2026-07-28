---
title: AddSort()
second_title: Aspose.Slides dla C++ – Referencja API
description: Gdy zostanie nadpisana w klasie pochodnej, sortuje węzły wybrane przez wyrażenie XPath zgodnie z określonym obiektem IComparer.
type: docs
weight: 27
url: /pl/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) metoda


When overridden in a derived class, sorts the nodes selected by the [XPath](../../) expression according to the specified IComparer object.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Obiekt reprezentujący klucz sortowania. Może to być wartość **string** węzła lub obiekt [XPathExpression](../) z skompilowanym wyrażeniem [XPath](../../). |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Obiekt IComparer zapewniający specyficzne porównania typów danych dla porównywania dwóch obiektów pod kątem równoważności. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) metoda


When overridden in a derived class, sorts the nodes selected by the [XPath](../../) expression according to the supplied parameters.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Obiekt reprezentujący klucz sortowania. Może to być wartość **string** węzła lub obiekt [XPathExpression](../) z skompilowanym wyrażeniem [XPath](../../). |
| order | [XmlSortOrder](../../xmlsortorder/) | Wartość XmlSortOrder określająca kolejność sortowania. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Wartość XmlCaseOrder określająca sposób sortowania wielkich i małych liter. |
| lang | [String](../../../system/string/) | Język używany do porównania. Używa klasy [Globalization::CultureInfo](../../../system.globalization/cultureinfo/), którą można przekazać do metody [String::Compare](../../../system/string/compare/) dla typów językowych, np. „us-en” dla amerykańskiego angielskiego. Jeśli podany zostanie pusty ciąg, używane jest środowisko systemowe do określenia [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | Wartość XmlDataType określająca kolejność sortowania dla typu danych. |

## Zobacz także

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [IComparer](../../../system.collections.generic/icomparer/)
* Klasa [XPathExpression](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)
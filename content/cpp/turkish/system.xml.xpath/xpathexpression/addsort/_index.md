---
title: AddSort()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, XPath ifadesi tarafından seçilen düğümleri belirtilen IComparer nesnesine göre sıralar.
type: docs
weight: 27
url: /tr/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) method

Türetilmiş bir sınıfta geçersiz kılındığında, [XPath](../../) ifadesi tarafından seçilen düğümleri belirtilen IComparer nesnesine göre sıralar.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Sıralama anahtarını temsil eden bir nesne. Bu, düğümün **string** değeri veya derlenmiş [XPath](../../) ifadesine sahip bir [XPathExpression](../) nesnesi olabilir. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | İki nesneyi eşdeğerlik açısından karşılaştırmak için belirli veri tipi karşılaştırmalarını sağlayan bir IComparer nesnesi. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) method

Türetilmiş bir sınıfta geçersiz kılındığında, [XPath](../../) ifadesi tarafından seçilen düğümleri sağlanan parametrelere göre sıralar.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Sıralama anahtarını temsil eden bir nesne. Bu, düğümün **string** değeri veya derlenmiş [XPath](../../) ifadesine sahip bir [XPathExpression](../) nesnesi olabilir. |
| order | [XmlSortOrder](../../xmlsortorder/) | Sıralama sırasını belirten bir XmlSortOrder değeri. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Büyük ve küçük harfleri nasıl sıralayacağını belirten bir XmlCaseOrder değeri. |
| lang | [String](../../../system/string/) | Karşılaştırma için kullanılacak dil. Dil tipleri için [String::Compare](../../../system/string/compare/) yöntemine geçilebilen [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) sınıfını kullanır, örneğin, "us-en" için ABD İngilizcesi. Boş bir dize belirtilirse, sistem ortamı [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) belirlemek için kullanılır. |
| dataType | [XmlDataType](../../xmldatatype/) | Veri tipi için sıralama düzenini belirten bir XmlDataType değeri. |

## İlgili

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [IComparer](../../../system.collections.generic/icomparer/)
* Sınıf [XPathExpression](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)
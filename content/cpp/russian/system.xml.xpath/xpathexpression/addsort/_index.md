---
title: AddSort()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе сортирует узлы, выбранные выражением XPath, в соответствии с указанным объектом IComparer.
type: docs
weight: 27
url: /ru/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) method


Когда переопределён в производном классе, сортирует узлы, выбранные выражением [XPath](../../), в соответствии с указанным объектом IComparer.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Объект, представляющий ключ сортировки. Это может быть значение **string** узла или объект [XPathExpression](../) с скомпилированным выражением [XPath](../../). |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Объект IComparer, предоставляющий сравнения конкретных типов данных для сравнения двух объектов на эквивалентность. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) method


Когда переопределён в производном классе, сортирует узлы, выбранные выражением [XPath](../../), в соответствии с переданными параметрами.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Объект, представляющий ключ сортировки. Это может быть значение **string** узла или объект [XPathExpression](../) с скомпилированным выражением [XPath](../../). |
| order | [XmlSortOrder](../../xmlsortorder/) | Значение XmlSortOrder, указывающее порядок сортировки. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Значение XmlCaseOrder, указывающее способ сортировки заглавных и строчных букв. |
| lang | [String](../../../system/string/) | Язык, используемый для сравнения. Используется класс [Globalization::CultureInfo](../../../system.globalization/cultureinfo/), который может быть передан в метод [String::Compare](../../../system/string/compare/) для указания языковых типов, например, «us-en» для американского английского. Если указана пустая строка, используется системная среда для определения [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | Значение XmlDataType, указывающее порядок сортировки для типа данных. |

## See Also

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
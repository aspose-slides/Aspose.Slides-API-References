---
title: AddSort()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: عند إعادة تعريفها في فئة مشتقة، تقوم بترتيب العقد التي تم اختيارها بواسطة تعبير XPath وفقًا لكائن IComparer المحدد.
type: docs
weight: 27
url: /ar/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) طريقة

عند إعادة تعريفها في فئة مشتقة، تقوم بترتيب العقد التي تم اختيارها بواسطة تعبير [XPath](../../) وفقًا لكائن IComparer المحدد.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | كائن يمثل مفتاح الفرز. يمكن أن يكون قيمة **string** للعقدة أو كائن [XPathExpression](../) مع تعبير [XPath](../../) مَجمَّع. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | كائن IComparer الذي يوفر مقارنات نوع البيانات المحددة لمقارنة كائنين للتأكد من التساوي. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) طريقة

عند إعادة تعريفها في فئة مشتقة، تقوم بترتيب العقد التي تم اختيارها بواسطة تعبير [XPath](../../) وفقًا للمعايير المقدَّمة.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | كائن يمثل مفتاح الفرز. يمكن أن يكون قيمة **string** للعقدة أو كائن [XPathExpression](../) مع تعبير [XPath](../../) مُجمَّع. |
| order | [XmlSortOrder](../../xmlsortorder/) | قيمة XmlSortOrder تشير إلى ترتيب الفرز. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | قيمة XmlCaseOrder توضح طريقة فرز الأحرف الكبيرة والصغيرة. |
| lang | [String](../../../system/string/) | اللغة المستخدمة للمقارنة. يستخدم الفئة [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) التي يمكن تمريرها إلى طريقة [String::Compare](../../../system/string/compare/) لأنواع اللغات، على سبيل المثال، "us-en" للإنجليزية الأمريكية. إذا تم تحديد سلسلة فارغة، يتم استخدام بيئة النظام لتحديد [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | قيمة XmlDataType تشير إلى ترتيب الفرز لنوع البيانات. |

## انظر أيضًا

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
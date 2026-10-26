---
title: AddSort()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride dalam kelas turunan, mengurutkan node yang dipilih oleh ekspresi XPath sesuai dengan objek IComparer yang ditentukan.
type: docs
weight: 27
url: /id/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) metode

Saat dioverride dalam kelas turunan, mengurutkan node yang dipilih oleh ekspresi [XPath](../../) sesuai dengan objek IComparer yang ditentukan.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Sebuah objek yang mewakili kunci urutan. Ini dapat berupa nilai **string** dari node atau objek [XPathExpression](../) dengan ekspresi [XPath](../../) yang telah dikompilasi. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Sebuah objek IComparer yang menyediakan perbandingan tipe data spesifik untuk membandingkan dua objek demi kesetaraan. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) metode

Saat dioverride dalam kelas turunan, mengurutkan node yang dipilih oleh ekspresi [XPath](../../) sesuai dengan parameter yang diberikan.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Sebuah objek yang mewakili kunci urutan. Ini dapat berupa nilai **string** dari node atau objek [XPathExpression](../) dengan ekspresi [XPath](../../) yang telah dikompilasi. |
| order | [XmlSortOrder](../../xmlsortorder/) | Nilai XmlSortOrder yang menunjukkan urutan penyortiran. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Nilai XmlCaseOrder yang menunjukkan cara mengurutkan huruf kapital dan huruf kecil. |
| lang | [String](../../../system/string/) | Bahasa yang digunakan untuk perbandingan. Menggunakan kelas [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) yang dapat diteruskan ke metode [String::Compare](../../../system/string/compare/) untuk tipe bahasa, misalnya, "us-en" untuk Bahasa Inggris AS. Jika string kosong diberikan, lingkungan sistem akan digunakan untuk menentukan [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | Nilai XmlDataType yang menunjukkan urutan penyortiran untuk tipe data. |

## Lihat Juga

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
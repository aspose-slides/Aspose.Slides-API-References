---
title: AddSort()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定された IComparer オブジェクトに従って XPath 式で選択されたノードをソートします。
type: docs
weight: 27
url: /ja/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) メソッド


派生クラスでオーバーライドされた場合、[XPath](../../) 式によって選択されたノードを、指定された IComparer オブジェクトに従ってソートします。

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ソートキーを表すオブジェクトです。これはノードの **string** 値、またはコンパイル済み [XPath](../../) 式を持つ [XPathExpression](../) オブジェクトにすることができます。 |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | 2 つのオブジェクトの等価性を比較するための特定のデータ型比較を提供する IComparer オブジェクトです。 |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) メソッド


派生クラスでオーバーライドされた場合、[XPath](../../) 式によって選択されたノードを、指定されたパラメータに従ってソートします。

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ソートキーを表すオブジェクトです。これはノードの **string** 値、またはコンパイル済み [XPath](../../) 式を持つ [XPathExpression](../) オブジェクトにすることができます。 |
| order | [XmlSortOrder](../../xmlsortorder/) | ソート順序を示す XmlSortOrder 値です。 |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | 大文字と小文字のソート方法を示す XmlCaseOrder 値です。 |
| lang | [String](../../../system/string/) | 比較に使用する言語です。言語タイプ用に [String::Compare](../../../system/string/compare/) メソッドに渡すことができる [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) クラスを使用します。例として、米国英語の場合は "us-en" を使用します。空文字列が指定された場合、システム環境が [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) を決定するために使用されます。 |
| dataType | [XmlDataType](../../xmldatatype/) | データ型のソート順序を示す XmlDataType 値です。 |

## 参照

* 列挙型 [XmlSortOrder](../../xmlsortorder/)
* 列挙型 [XmlCaseOrder](../../xmlcaseorder/)
* 列挙型 [XmlDataType](../../xmldatatype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [IComparer](../../../system.collections.generic/icomparer/)
* クラス [XPathExpression](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)
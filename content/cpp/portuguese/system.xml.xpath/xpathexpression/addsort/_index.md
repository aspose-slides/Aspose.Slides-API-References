---
title: AddSort()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, classifica os nós selecionados pela expressão XPath de acordo com o objeto IComparer especificado.
type: docs
weight: 27
url: /pt/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) método


Quando sobrescrito em uma classe derivada, classifica os nós selecionados pela expressão [XPath](../../) de acordo com o objeto IComparer especificado.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Um objeto que representa a chave de ordenação. Pode ser o valor **string** do nó ou um objeto [XPathExpression](../) com uma expressão [XPath](../../) compilada. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Um objeto IComparer que fornece as comparações de tipos de dados específicos para comparar dois objetos quanto à equivalência. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) método


Quando sobrescrito em uma classe derivada, classifica os nós selecionados pela expressão [XPath](../../) de acordo com os parâmetros fornecidos.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Um objeto que representa a chave de ordenação. Pode ser o valor **string** do nó ou um objeto [XPathExpression](../) com uma expressão [XPath](../../) compilada. |
| order | [XmlSortOrder](../../xmlsortorder/) | Um valor XmlSortOrder que indica a ordem de classificação. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Um valor XmlCaseOrder que indica como classificar letras maiúsculas e minúsculas. |
| lang | [String](../../../system/string/) | O idioma a ser usado para comparação. Utiliza a classe [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) que pode ser passada ao método [String::Compare](../../../system/string/compare/) para os tipos de idioma, por exemplo, "us-en" para o inglês dos EUA. Se uma string vazia for especificada, o ambiente do sistema será usado para determinar o [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | Um valor XmlDataType que indica a ordem de classificação para o tipo de dados. |

## Veja Também

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
---
title: AddSort()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, trie les nœuds sélectionnés par l'expression XPath selon l'objet IComparer spécifié.
type: docs
weight: 27
url: /fr/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) méthode


Lorsqu'elle est remplacée dans une classe dérivée, trie les nœuds sélectionnés par l'expression [XPath](../../) selon l'objet IComparer spécifié.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Un objet représentant la clé de tri. Il peut s'agir de la valeur **string** du nœud ou d'un objet [XPathExpression](../) avec une expression [XPath](../../) compilée. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Un objet IComparer qui fournit les comparaisons de types de données spécifiques pour comparer deux objets en vue d'établir leur équivalence. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) méthode


Lorsqu'elle est remplacée dans une classe dérivée, trie les nœuds sélectionnés par l'expression [XPath](../../) selon les paramètres fournis.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Un objet représentant la clé de tri. Il peut s'agir de la valeur **string** du nœud ou d'un objet [XPathExpression](../) avec une expression [XPath](../../) compilée. |
| order | [XmlSortOrder](../../xmlsortorder/) | Une valeur XmlSortOrder indiquant l'ordre de tri. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Une valeur XmlCaseOrder indiquant comment trier les lettres majuscules et minuscules. |
| lang | [String](../../../system/string/) | La langue à utiliser pour la comparaison. Utilise la classe [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) qui peut être transmise à la méthode [String::Compare](../../../system/string/compare/) pour les types de langue, par exemple \"us-en\" pour l'anglais américain. Si une chaîne vide est spécifiée, l'environnement système est utilisé pour déterminer le [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | Une valeur XmlDataType indiquant l'ordre de tri pour le type de données. |

## Voir aussi

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
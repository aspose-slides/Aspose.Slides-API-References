---
title: AddSort()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, ordina i nodi selezionati dall'espressione XPath secondo l'oggetto IComparer specificato.
type: docs
weight: 27
url: /it/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) metodo

Quando sovrascritto in una classe derivata, ordina i nodi selezionati dall'espressione [XPath](../../) secondo l'oggetto IComparer specificato.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Un oggetto che rappresenta la chiave di ordinamento. Può essere il valore **string** del nodo o un oggetto [XPathExpression](../) con un'espressione [XPath](../../) compilata. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Un oggetto IComparer che fornisce i confronti specifici del tipo di dati per confrontare due oggetti per equivalenza. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) metodo

Quando sovrascritto in una classe derivata, ordina i nodi selezionati dall'espressione [XPath](../../) secondo i parametri forniti.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Un oggetto che rappresenta la chiave di ordinamento. Può essere il valore **string** del nodo o un oggetto [XPathExpression](../) con un'espressione [XPath](../../) compilata. |
| order | [XmlSortOrder](../../xmlsortorder/) | Un valore XmlSortOrder che indica l'ordine di ordinamento. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Un valore XmlCaseOrder che indica come ordinare le lettere maiuscole e minuscole. |
| lang | [String](../../../system/string/) | La lingua da usare per il confronto. Utilizza la classe [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) che può essere passata al metodo [String::Compare](../../../system/string/compare/) per i tipi di lingua, per esempio, "us-en" per l'inglese statunitense. Se viene specificata una stringa vuota, viene usato l'ambiente di sistema per determinare il [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | Un valore XmlDataType che indica l'ordine di ordinamento per il tipo di dati. |

## Vedi anche

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
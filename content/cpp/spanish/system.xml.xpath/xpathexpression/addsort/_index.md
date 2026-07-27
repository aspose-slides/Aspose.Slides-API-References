---
title: AddSort()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se anula en una clase derivada, ordena los nodos seleccionados por la expresión XPath de acuerdo con el objeto IComparer especificado.
type: docs
weight: 27
url: /es/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) método

Cuando se anula en una clase derivada, ordena los nodos seleccionados por la expresión [XPath](../../) según el objeto IComparer especificado.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Un objeto que representa la clave de ordenamiento. Esto puede ser el valor **string** del nodo o un objeto [XPathExpression](../) con una expresión [XPath](../../) compilada. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | Un objeto IComparer que provee las comparaciones de tipos de datos específicos para comparar dos objetos en busca de equivalencia. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) método

Cuando se anula en una clase derivada, ordena los nodos seleccionados por la expresión [XPath](../../) de acuerdo con los parámetros suministrados.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Un objeto que representa la clave de ordenamiento. Esto puede ser el valor **string** del nodo o un objeto [XPathExpression](../) con una expresión [XPath](../../) compilada. |
| order | [XmlSortOrder](../../xmlsortorder/) | Un valor XmlSortOrder que indica el orden de clasificación. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | Un valor XmlCaseOrder que indica cómo ordenar las letras mayúsculas y minúsculas. |
| lang | [String](../../../system/string/) | El idioma a usar para la comparación. Utiliza la clase [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) que puede pasarse al método [String::Compare](../../../system/string/compare/) para los tipos de idioma, por ejemplo, "us-en" para inglés de EE. UU. Si se especifica una cadena vacía, se usa el entorno del sistema para determinar el [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | Un valor XmlDataType que indica el orden de clasificación para el tipo de datos. |

## Ver también

* Enumeración [XmlSortOrder](../../xmlsortorder/)
* Enumeración [XmlCaseOrder](../../xmlcaseorder/)
* Enumeración [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [IComparer](../../../system.collections.generic/icomparer/)
* Clase [XPathExpression](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)
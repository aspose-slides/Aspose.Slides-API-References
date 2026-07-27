---
title: IsDerivedFrom()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um valor que indica se o tipo de esquema derivado especificado é derivado do tipo de esquema base especificado.
type: docs
weight: 209
url: /pt/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) método

Retorna um valor que indica se o tipo de esquema derivado especificado é derivado do tipo de esquema base especificado.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | O [XmlSchemaType](../) derivado a ser testado. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | O [XmlSchemaType](../) base para testar o [XmlSchemaType](../) derivado. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Um dos valores de XmlSchemaDerivationMethod que representa um método de derivação de tipo a ser excluído do teste. |

### Valor de Retorno

**true** se o tipo derivado for derivado do tipo base; caso contrário, **false**.

## Ver Também

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchemaType](../)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)
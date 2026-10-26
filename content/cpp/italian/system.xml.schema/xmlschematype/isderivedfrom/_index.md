---
title: IsDerivedFrom()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un valore che indica se il tipo di schema derivato specificato è derivato dal tipo di schema base specificato.
type: docs
weight: 209
url: /it/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) metodo

Restituisce un valore che indica se il tipo di schema derivato specificato è derivato dal tipo di schema base specificato.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | Il [XmlSchemaType](../) derivato da testare. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | Il [XmlSchemaType](../) base contro cui verificare il [XmlSchemaType](../) derivato. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Uno dei valori di XmlSchemaDerivationMethod che rappresenta un metodo di derivazione del tipo da escludere dal test. |

### Valore restituito

**true** se il tipo derivato è derivato dal tipo base; altrimenti, **false**.

## Vedi anche

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchemaType](../)
* Spazio dei nomi [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)
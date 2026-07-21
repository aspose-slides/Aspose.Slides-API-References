---
title: IsDerivedFrom()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает значение, указывающее, является ли указанный производный тип схемы производным от указанного базового типа схемы.
type: docs
weight: 209
url: /ru/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) method

Возвращает значение, указывающее, выводится ли указанный производный тип схемы из указанного базового типа схемы.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | Производный [XmlSchemaType](../) для проверки. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | Базовый [XmlSchemaType](../), относительно которого проверяется производный [XmlSchemaType](../). |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Одно из значений XmlSchemaDerivationMethod, представляющее метод вывода типа, который следует исключить из проверки. |

### Возвращаемое значение

**true** если производный тип выводится из базового типа; в противном случае **false**.

## См. также

* Перечисление [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchemaType](../)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)
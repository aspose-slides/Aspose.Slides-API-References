---
title: GetUnspecifiedDefaultAttributes()
second_title: Referência da API Aspose.Slides para C++
description: "Valida restrições de identidade nos atributos padrão e preenche a List especificada com objetos XmlSchemaAttribute para quaisquer atributos com valores padrão que não foram previamente validados usando o método XmlSchemaValidator::ValidateAttribute no contexto do elemento."
type: docs
weight: 157
url: /pt/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) método

Valida restrições de identidade nos atributos padrão e preenche a List especificada com objetos [XmlSchemaAttribute](../../xmlschemaattribute/) para quaisquer atributos com valores padrão que ainda não foram validados previamente usando o método [XmlSchemaValidator::ValidateAttribute](../validateattribute/) no contexto do elemento.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | Uma List a ser preenchida com objetos [XmlSchemaAttribute](../../xmlschemaattribute/) para quaisquer atributos ainda não encontrados durante a validação no contexto do elemento. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [List](../../../system.collections.generic/list/)
* Classe [Object](../../../system/object/)
* Classe [XmlSchemaValidator](../)
* Espaço de nomes [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)
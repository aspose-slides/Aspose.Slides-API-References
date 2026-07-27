---
title: Compile()
second_title: Aspose.Slides para C++ Referência de API
description: Compila o Modelo de Objeto de Esquema XML (SOM) em informações de esquema para validação. Usado para verificar a estrutura sintática e semântica do SOM construído programaticamente. A verificação de validação semântica é realizada durante a compilação.
type: docs
weight: 352
url: /pt/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) método


Compila o Modelo XML [Schema](../../)[Object](../../../system/object/) (SOM) em informações de esquema para validação. Usado para verificar a estrutura sintática e semântica do SOM construído programaticamente. A verificação de validação semântica é realizada durante a compilação.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | O manipulador de eventos de validação que recebe informações sobre erros de validação XML [Schema](../../). |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) método


Compila o Modelo XML [Schema](../../)[Object](../../../system/object/) (SOM) em informações de esquema para validação. Usado para verificar a estrutura sintática e semântica do SOM construído programaticamente. A verificação de validação semântica é realizada durante a compilação.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | O manipulador de eventos de validação que recebe informações sobre os erros de validação XML [Schema](../../). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver namespaces referenciados nos elementos **include** e **import**. |

## Ver Também

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../)
* Classe [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)
---
title: CreateXmlDeclaration()
second_title: Aspose.Slides para C++ Referência da API
description: Cria um nó XmlDeclaration com os valores especificados.
type: docs
weight: 378
url: /pt/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) método

Cria um nó [XmlDeclaration](../../xmldeclaration/) com os valores especificados.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | A versão deve ser "1.0". |
| encoding | const [String](../../../system/string/)\& | O valor do atributo de codificação. Esta é a codificação usada ao salvar o [XmlDocument](../) em um arquivo ou fluxo; portanto, deve ser definido como uma string suportada pela classe [Text::Encoding](../../../system.text/encoding/), caso contrário "XmlDocument::Save(String)" falha. Se for **nullptr** ou [String::Empty](../../../system/string/empty/), o método [XmlDocument::Save](../save/) não grava um atributo de codificação na declaração XML e, portanto, a codificação padrão, UTF-8, é usada. |
| standalone | const [String](../../../system/string/)\& | O valor deve ser "yes" ou "no". Se for **nullptr** ou [String::Empty](../../../system/string/empty/), o método [XmlDocument::Save](../save/) não grava um atributo standalone na declaração XML. |

### Valor de Retorno

O novo nó [XmlDeclaration](../../xmldeclaration/).

## Observações

Nota: Se o [XmlDocument](../) for salvo em um TextWriter ou em um [XmlTextWriter](../../xmltextwriter/), esse valor de codificação é descartado. Em vez disso, a codificação do TextWriter ou do [XmlTextWriter](../../xmltextwriter/) é usada. Isso garante que o XML escrito possa ser lido novamente usando a codificação correta.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlDeclaration](../../xmldeclaration/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
---
title: WriteNode()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, copia tudo do leitor para o gravador e move o leitor para o início do próximo irmão.
type: docs
weight: 430
url: /pt/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) método


Quando sobrescrito em uma classe derivada, copia tudo do leitor para o gravador e move o leitor para o início do próximo irmão.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | O [XmlReader](../../xmlreader/) para ler. |
| defattr | **bool** | **true** para copiar os atributos padrão do [XmlReader](../../xmlreader/); caso contrário, **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) método


Copia tudo do objeto XPathNavigator para o gravador. A posição do XPathNavigator permanece inalterada.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | O XPathNavigator para copiar. |
| defattr | **bool** | **true** para copiar os atributos padrão; caso contrário, **false**. |

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../xmlreader/)
* Classe [XmlWriter](../)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
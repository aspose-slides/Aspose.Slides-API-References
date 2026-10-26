---
title: CreateXmlDeclaration()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nodo XmlDeclaration con i valori specificati.
type: docs
weight: 378
url: /it/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String&, const String&, const String&) metodo


Crea un [XmlDeclaration](../../xmldeclaration/) node con i valori specificati.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | La versione deve essere "1.0". |
| encoding | const [String](../../../system/string/)\& | Il valore dell'attributo encoding. Questo è l'encoding usato quando si salva il [XmlDocument](../) in un file o in uno stream; pertanto, deve essere impostato a una stringa supportata dalla classe [Text::Encoding](../../../system.text/encoding/), altrimenti "XmlDocument::Save(String)" fallisce. Se questo è **nullptr** o [String::Empty](../../../system/string/empty/), il metodo [XmlDocument::Save](../save/) non scrive un attributo encoding nella dichiarazione XML e quindi viene usato l'encoding predefinito, UTF-8. |
| standalone | const [String](../../../system/string/)\& | Il valore deve essere "yes" oppure "no". Se questo è **nullptr** o [String::Empty](../../../system/string/empty/), il metodo [XmlDocument::Save](../save/) non scrive un attributo standalone nella dichiarazione XML. |

### Valore restituito

Il nuovo nodo [XmlDeclaration](../../xmldeclaration/).

## Osservazioni

Nota: Se il [XmlDocument](../) viene salvato su un TextWriter o su un [XmlTextWriter](../../xmltextwriter/), questo valore di encoding viene scartato. Invece, viene usato l'encoding del TextWriter o del [XmlTextWriter](../../xmltextwriter/). Ciò garantisce che l'XML scritto possa essere letto nuovamente usando l'encoding corretto. 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDeclaration](../../xmldeclaration/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
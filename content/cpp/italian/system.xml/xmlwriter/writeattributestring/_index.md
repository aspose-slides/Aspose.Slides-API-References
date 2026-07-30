---
title: WriteAttributeString()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, scrive un attributo con il nome locale, l'URI dello spazio dei nomi e il valore specificati.
type: docs
weight: 131
url: /it/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) metodo

Quando sovrascritto in una classe derivata, scrive un attributo con il nome locale, l'URI dello spazio dei nomi e il valore specificati.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'attributo. |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi da associare all'attributo. |
| value | const [String](../../../system/string/)\& | Il valore dell'attributo. |

## XmlWriter::WriteAttributeString(const String\&, const String\&) metodo

Quando sovrascritto in una classe derivata, emette l'attributo con il nome locale e il valore specificati.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'attributo. |
| value | const [String](../../../system/string/)\& | Il valore dell'attributo. |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) metodo

Quando sovrascritto in una classe derivata, emette l'attributo con il prefisso, il nome locale, l'URI dello spazio dei nomi e il valore specificati.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso dello spazio dei nomi dell'attributo. |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'attributo. |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi dell'attributo. |
| value | const [String](../../../system/string/)\& | Il valore dell'attributo. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)
---
title: WriteStartAttribute()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive l'inizio di un attributo con il nome locale e l'URI dello spazio dei nomi specificati.
type: docs
weight: 144
url: /it/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) metodo

Scrive l'inizio di un attributo con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'attributo. |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi dell'attributo. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) metodo

Quando sovrascritto in una classe derivata, scrive l'inizio di un attributo con il prefisso, il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Il prefisso dello spazio dei nomi dell'attributo. |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'attributo. |
| ns | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi per l'attributo. |

## XmlWriter::WriteStartAttribute(const String\&) metodo

Scrive l'inizio di un attributo con il nome locale specificato.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Il nome locale dell'attributo. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)
---
title: ValidateWhitespace()
second_title: Riferimento API di Aspose.Slides per C++
description: Convalida se gli spazi bianchi nella string specificata sono consentiti nel contesto dell'elemento corrente e accumula gli spazi bianchi per la convalida se l'elemento corrente ha contenuto semplice.
type: docs
weight: 196
url: /it/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) metodo

Convalida se gli spazi bianchi nella **string** specificata sono consentiti nel contesto dell'elemento corrente e accumula gli spazi bianchi per la convalida se l'elemento corrente ha contenuto semplice.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Una **string** di spazi bianchi da convalidare nel contesto dell'elemento corrente. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) metodo

Convalida se gli spazi bianchi restituiti dall'oggetto XmlValueGetter specificato sono consentiti nel contesto dell'elemento corrente e accumula gli spazi bianchi per la convalida se l'elemento corrente ha contenuto semplice.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Un callback XmlValueGetter usato per passare il valore degli spazi bianchi come un tipo compatibile con il tipo XML [Schema](../../) Definition Language (XSD) dell'attributo. |

## Vedi anche

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaValidator](../)
* Spazio dei nomi [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
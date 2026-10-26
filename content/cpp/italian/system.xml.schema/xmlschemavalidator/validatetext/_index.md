---
title: ValidateText()
second_title: Riferimento API di Aspose.Slides per C++
description: Convalida se la stringa di testo specificata è consentita nel contesto dell'elemento corrente e accumula il testo per la convalida se l'elemento corrente ha contenuto semplice.
type: docs
weight: 183
url: /it/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) metodo

Convalida se la **string** di testo specificata è consentita nel contesto dell'elemento corrente e accumula il testo per la convalida se l'elemento corrente ha contenuto semplice.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Una **string** di testo da convalidare nel contesto dell'elemento corrente. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) metodo

Convalida se il testo restituito dall'oggetto XmlValueGetter specificato è consentito nel contesto dell'elemento corrente e accumula il testo per la convalida se l'elemento corrente ha contenuto semplice.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Un callback XmlValueGetter usato per passare il valore del testo come un tipo compatibile con il tipo XML [Schema](../../) Definition Language (XSD) dell'attributo. |

## Vedi anche

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaValidator](../)
* Spazio dei nomi [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)
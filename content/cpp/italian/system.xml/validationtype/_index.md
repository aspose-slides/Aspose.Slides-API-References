---
title: ValidationType
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica il tipo di validazione da eseguire.
type: docs
weight: 729
url: /it/system.xml/validationtype/
---
## ValidationType enum

Specifica il tipo di validazione da eseguire.

```cpp
enum class ValidationType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Non viene eseguita alcuna convalida e non vengono generati errori di convalida. Questa impostazione crea un parser non convalidante conforme a XML 1.0. |
| Auto | 1 | Esegue la convalida se vengono trovate informazioni DTD o di schema. |
| DTD | 2 | Esegue la convalida secondo il DTD. |
| XDR | 3 | Convalida secondo gli schemi XML-Data Reduced (XDR), includendo gli schemi XDR inline. Gli schemi XDR sono riconosciuti usando il prefisso di namespace **x-schema** o il valore [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Convalida secondo gli schemi XML [Schema](../../system.xml.schema/) definition language (XSD), includendo gli XML Schema inline. Gli XML Schema sono associati a URI di namespace sia usando l'attributo **schemaLocation** sia i **Schemas** forniti. |

## Vedi anche

* Spazio dei nomi [System::Xml](../)
* Libreria [Aspose.Slides](../../)
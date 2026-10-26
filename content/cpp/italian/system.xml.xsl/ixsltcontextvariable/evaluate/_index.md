---
title: Evaluate()
second_title: Riferimento API di Aspose.Slides per C++
description: Valuta la variabile in fase di esecuzione e restituisce un oggetto che rappresenta il valore della variabile.
type: docs
weight: 40
url: /it/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) metodo

Valuta la variabile in fase di esecuzione e restituisce un oggetto che rappresenta il valore della variabile.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Un [XsltContext](../../xsltcontext/) che rappresenta il contesto di esecuzione della variabile. |

### Valore di ritorno

Un [Object](../../../system/object/) che rappresenta il valore della variabile. I possibili tipi di ritorno includono number, string, [Boolean](../../../system/boolean/), document fragment o node set.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XsltContext](../../xsltcontext/)
* Classe [IXsltContextVariable](../)
* Spazio dei nomi [System::Xml::Xsl](../../)
* Libreria [Aspose.Slides](../../../)
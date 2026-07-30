---
title: get_Encoding()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il livello di codifica del documento XML.
type: docs
weight: 14
url: /it/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() metodo

Restituisce il livello di codifica del documento XML.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### Valore di ritorno

Il nome valido della codifica dei caratteri.
## Osservazioni

I nomi di codifica dei caratteri più comunemente supportati per XML sono i seguenti: 

| Categoria | Nomi di codifica |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Questo valore è opzionale. Se un valore non è impostato, questo metodo restituisce [String::Empty](../../../system/string/empty/). Se un attributo di codifica non è incluso, si assume la codifica UTF-8 quando il documento viene scritto o salvato. 
## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlDeclaration](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)
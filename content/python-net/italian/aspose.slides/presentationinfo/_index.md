---
title: PresentationInfo class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/presentationinfo/
---
## PresentationInfo classe

Informazioni sul file di presentazione

Il tipo PresentationInfo espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`is_encrypted`](/slides/python-net/it/aspose.slides/presentationinfo/is_encrypted/) | Restituisce True se la presentazione collegata è crittografata, altrimenti False.<br/>            Sola lettura **bool**. |
| [`is_password_protected`](/slides/python-net/it/aspose.slides/presentationinfo/is_password_protected/) | Restituisce un valore che indica se la presentazione collegata è protetta da una password di apertura. |
| [`is_write_protected`](/slides/python-net/it/aspose.slides/presentationinfo/is_write_protected/) | Restituisce un valore che indica se la presentazione collegata è protetta da scrittura. |
| [`load_format`](/slides/python-net/it/aspose.slides/presentationinfo/load_format/) | Restituisce il formato della presentazione collegata.<br/>            Sola lettura [`LoadFormat`](/slides/python-net/it/aspose.slides/loadformat). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/it/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | Scrive la presentazione collegata su un flusso. |
| [`write_binded_presentation(self, file)`](/slides/python-net/it/aspose.slides/presentationinfo/write_binded_presentation/#str) | Scrive la presentazione collegata su file. |
| [`check_password(self, password)`](/slides/python-net/it/aspose.slides/presentationinfo/check_password/#str) | Verifica se una password è corretta per una presentazione protetta da password di apertura. |
| [`check_write_protection(self, password)`](/slides/python-net/it/aspose.slides/presentationinfo/check_write_protection/#str) | Verifica se la password di modifica è corretta per una presentazione protetta da scrittura. |
| [`read_document_properties(self)`](/slides/python-net/it/aspose.slides/presentationinfo/read_document_properties/#) | Restituisce le proprietà del documento della presentazione collegata. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/it/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | Aggiorna le proprietà della presentazione collegata. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)
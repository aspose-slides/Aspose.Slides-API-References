---
title: ProtectionManager class
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/protectionmanager/
---
## ProtectionManager classe

Gestione della protezione con password delle presentazioni.

Il tipo ProtectionManager espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/it/aspose.slides/protectionmanager/encrypt_document_properties/) | Questa proprietà ha senso, se la presentazione è protetta da password.<br/>            Se true allora le proprietà del documento sono criptate nel file della presentazione.<br/>            Se false allora le proprietà del documento sono pubbliche mentre la presentazione è criptata.<br/>            Lettura/scrittura **bool**. |
| [`is_encrypted`](/slides/python-net/it/aspose.slides/protectionmanager/is_encrypted/) | Restituisce un valore che indica se questa istanza è crittografata.<br/>            Solo lettura **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/it/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Questa proprietà ha senso, se il file di presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche.<br/>            Il valore true indica che solo le proprietà del documento sono caricate da un file di presentazione crittografato senza utilizzare la password.<br/>            Il valore false indica che l'intera presentazione crittografata è caricata usando la password corretta, non solo le proprietà del documento vengono caricate.<br/>            Se la presentazione non è crittografata, il valore della proprietà è sempre false.<br/>            Se le proprietà del documento di un file crittografato non sono pubbliche, il valore della proprietà è sempre false.<br/>            Se Presentation.EncryptDocumentProperties è true, allora il valore della proprietà IsOnlyDocumentPropertiesLoaded è sempre false.<br/>            Solo lettura **bool**. |
| [`is_write_protected`](/slides/python-net/it/aspose.slides/protectionmanager/is_write_protected/) | Restituisce un valore che indica se questa presentazione è protetta da scrittura.<br/>            Solo lettura **bool**. |
| [`encryption_password`](/slides/python-net/it/aspose.slides/protectionmanager/encryption_password/) | Restituisce la password utilizzata per la crittografia della presentazione.<br/>            Solo lettura **str**. |
| [`read_only_recommended`](/slides/python-net/it/aspose.slides/protectionmanager/read_only_recommended/) | Restituisce o imposta la raccomandazione di sola lettura.<br/>            Lettura/scrittura **bool**. |

## Metodi

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/it/aspose.slides/protectionmanager/encrypt/#str) | Cifra la Presentazione con la password specificata. |
| [`remove_encryption(self)`](/slides/python-net/it/aspose.slides/protectionmanager/remove_encryption/#) | Rimuove la crittografia. |
| [`set_write_protection(self, password)`](/slides/python-net/it/aspose.slides/protectionmanager/set_write_protection/#str) | Imposta la protezione da scrittura per questa presentazione con la password specificata. |
| [`remove_write_protection(self)`](/slides/python-net/it/aspose.slides/protectionmanager/remove_write_protection/#) | Rimuove la protezione da scrittura per questa presentazione. |
| [`check_write_protection(self, password)`](/slides/python-net/it/aspose.slides/protectionmanager/check_write_protection/#str) | Determina se una presentazione è protetta da password per la modifica. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)
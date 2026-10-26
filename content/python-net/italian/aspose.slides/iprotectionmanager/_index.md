---
title: IProtectionManager class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/iprotectionmanager/
---
## IProtectionManager classe

Gestione della protezione con password della presentazione.

Il tipo IProtectionManager espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/it/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Questa proprietà ha senso se la presentazione è protetta da password.<br/>            Se true allora le proprietà del documento sono crittografate nel file della presentazione.<br/>            Se false allora le proprietà del documento sono pubbliche mentre la presentazione è crittografata.<br/>            Lettura/scrittura **bool**. |
| [`is_encrypted`](/slides/python-net/it/aspose.slides/iprotectionmanager/is_encrypted/) | Restituisce un valore che indica se questa istanza è crittografata.<br/>            Solo lettura **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/it/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Questa proprietà ha senso se il file della presentazione è protetto da password e le proprietà del documento di questo file sono pubbliche.<br/>            Il valore true indica che solo le proprietà del documento vengono caricate da un file di presentazione crittografato senza l'uso della password.<br/>            Il valore false indica che l'intera presentazione crittografata viene caricata usando la password corretta, non solo le proprietà del documento.<br/>            Se la presentazione non è crittografata, il valore della proprietà è sempre false.<br/>            Se le proprietà del documento di un file crittografato non sono pubbliche, il valore della proprietà è sempre false.<br/>            Se PresentationEx.EncryptDocumentProperties è true, allora il valore della proprietà IsOnlyDocumentPropertiesLoaded è sempre false.<br/>            Solo lettura **bool**. |
| [`is_write_protected`](/slides/python-net/it/aspose.slides/iprotectionmanager/is_write_protected/) | Restituisce un valore che indica se questa presentazione è protetta dalla scrittura.<br/>            Solo lettura **bool**. |
| [`encryption_password`](/slides/python-net/it/aspose.slides/iprotectionmanager/encryption_password/) | Restituisce la password di crittografia.<br/>            Solo lettura **str**. |
| [`read_only_recommended`](/slides/python-net/it/aspose.slides/iprotectionmanager/read_only_recommended/) | Restituisce o imposta la raccomandazione di sola lettura.<br/>            Lettura/scrittura **bool**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/it/aspose.slides/iprotectionmanager/encrypt/#str) | Cifra la presentazione con la password specificata. |
| [`remove_encryption(self)`](/slides/python-net/it/aspose.slides/iprotectionmanager/remove_encryption/#) | Rimuove la crittografia. |
| [`set_write_protection(self, password)`](/slides/python-net/it/aspose.slides/iprotectionmanager/set_write_protection/#str) | Imposta la protezione dalla scrittura per questa presentazione con la password specificata. |
| [`remove_write_protection(self)`](/slides/python-net/it/aspose.slides/iprotectionmanager/remove_write_protection/#) | Rimuove la protezione dalla scrittura per questa presentazione. |
| [`check_write_protection(self, password)`](/slides/python-net/it/aspose.slides/iprotectionmanager/check_write_protection/#str) | Determina se una presentazione è protetta da password per la modifica. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)
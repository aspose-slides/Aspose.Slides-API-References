---
title: PdfAccessPermissions
second_title: Riferimento API di Aspose.Slides per C++
description: Contiene un insieme di flag che specificano quali autorizzazioni di accesso devono essere concesse quando il documento viene aperto con accesso utente.
type: docs
weight: 989
url: /it/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Contiene un insieme di flag che specificano quali autorizzazioni di accesso devono essere concesse quando il documento viene aperto con accesso utente.

```cpp
enum class PdfAccessPermissions
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Specifica che un utente non dispone di autorizzazioni di accesso. |
| PrintDocument | 4 | Specifica se un utente può stampare il documento (potenzialmente non al livello di massima qualità, a seconda che il bit [PdfAccessPermissions::HighQualityPrint](./) sia anche impostato). |
| ModifyContent | 8 | Specifica se un utente può modificare il contenuto del documento mediante operazioni diverse da quelle controllate dai bit [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | Specifica se un utente può copiare o estrarre in altro modo testo e grafica dal documento mediante operazioni diverse da quelle controllate dal bit [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | Specifica se un utente può aggiungere o modificare annotazioni testuali, compilare campi di modulo interattivi e, se il bit [PdfAccessPermissions::ModifyContent](./) è anche impostato, creare o modificare campi di modulo interattivi (inclusi i campi firma). |
| FillExistingFields | 256 | Specifica se un utente può compilare campi di modulo interattivi esistenti (inclusi i campi firma), anche se il bit [PdfAccessPermissions::AddOrModifyFields](./) è non impostato. |
| ExtractTextAndGraphics | 512 | Specifica se un utente può estrarre testo e grafica a supporto dell'accessibilità per utenti con disabilità o per altri scopi. |
| AssembleDocument | 1024 | Specifica se un utente può assemblare il documento (inserire, ruotare o eliminare pagine e creare segnalibri o immagini in miniatura), anche se il bit [PdfAccessPermissions::ModifyContent](./) è non impostato. |
| HighQualityPrint | 2048 | Specifica se un utente può stampare il documento in una rappresentazione da cui potrebbe essere generata una copia digitale fedele del contenuto PDF. Quando questo bit è non impostato (e il bit [PdfAccessPermissions::PrintDocument](./) è impostato), la stampa è limitata a una rappresentazione a basso livello dell'aspetto, possibilmente di qualità ridotta. |

## Vedi anche

* Namespace [Aspose::Slides::Export](../)
* Libreria [Aspose.Slides](../../)
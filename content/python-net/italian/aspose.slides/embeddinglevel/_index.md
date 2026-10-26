---
title: EmbeddingLevel enumeration
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/embeddinglevel/
---
## Enumerazione EmbeddingLevel

Rappresenta i diritti di licenza per l'incorporamento del font.

Il tipo EmbeddingLevel espone i seguenti membri:

## Campi

| Field | Description |
| :- | :- |
| INSTALLABLE | Font con questa impostazione indicano che possono essere incorporati e installati permanentemente sul sistema remoto da un'applicazione. <br/>            L'utente del sistema remoto acquisisce gli stessi diritti, obblighi e licenze per quel font di quelli del compratore originale del font, <br/>            ed è soggetto allo stesso accordo di licenza per l'utente finale, copyright, brevetto di design e/o marchio come era per il compratore originale. |
| RESTRICTED | I font che hanno impostato solo questo bit non devono essere modificati, incorporati o scambiati in alcun modo senza prima ottenere il permesso del proprietario legale. |
| PREVIEW_PRINT | Quando questo bit è impostato, il font può essere incorporato e caricato temporaneamente sul sistema remoto. I documenti contenenti font Preview & <br/>            Print devono essere aperti in modalità "sola lettura"; non è possibile apportare modifiche al documento. |
| EDITABLE | Quando questo bit è impostato, il font può essere incorporato ma deve essere installato solo temporaneamente su altri sistemi. In contrasto con i font Preview & <br/>            Print, i documenti contenenti font Editable possono essere aperti in lettura, la modifica è consentita e le modifiche possono essere salvate. |
| NO_SUBSETTING | Quando questo bit è impostato, il font non può essere sottosettato prima dell'incorporamento. Si applicano anche le altre restrizioni di incorporamento specificate nei bit 0-3 e 9. |
| BITMAP_ONLY | Quando questo bit è impostato, solo le bitmap contenute nel font possono essere incorporate. Nessun dato di contorno può essere incorporato. Se non sono disponibili bitmap nel font, <br/>            il font è considerato non incorporabile e i servizi di incorporamento falliranno. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)
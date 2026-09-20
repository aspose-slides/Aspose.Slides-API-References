---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides per Python tramite .NET API Reference
description: 
type: docs
url: /it/aspose.slides.export/pdfaccesspermissions/
---
## Enumerazione PdfAccessPermissions

Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento è aperto con 
            l'accesso dell'utente.

Il tipo PdfAccessPermissions espone i seguenti membri:

## Campi

| Campo | Descrizione |
| :- | :- |
| NONE | Specifica che un utente non ha permessi di accesso. |
| PRINT_DOCUMENT | Specifica se un utente può stampare il documento (possibilmente non al livello di qualità più alto, a seconda di <br/>            se il bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) è anche impostato). |
| MODIFY_CONTENT | Specifica se un utente può modificare i contenuti del documento mediante operazioni diverse da quelle controllate<br/>            dai bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Specifica se un utente può copiare o altrimenti estrarre testo e grafica dal documento mediante operazioni <br/>            diverse da quelle controllate dal bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Specifica se un utente può aggiungere o modificare annotazioni di testo, compilare campi di modulo interattivi e, se il bit<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) è anche impostato, creare o modificare campi di modulo interattivi (inclusi i campi firma). |
| FILL_EXISTING_FIELDS | Specifica se un utente può compilare i campi di modulo interattivi esistenti (inclusi i campi firma), anche se<br/>            il bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) è cancellato. |
| EXTRACT_TEXT_AND_GRAPHICS | Specifica se un utente può estrarre testo e grafica a supporto dell'accessibilità per utenti con disabilità<br/>            o per altri scopi. |
| ASSEMBLE_DOCUMENT | Specifica se un utente può assemblare il documento (inserire, ruotare o eliminare pagine e creare segnalibri o<br/>            miniature), anche se il bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) è cancellato. |
| HIGH_QUALITY_PRINT | Specifica se un utente può stampare il documento in una rappresentazione da cui potrebbe essere generata una copia digitale fedele del<br/>            contenuto PDF. Quando questo bit è cancellato (e il bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/it/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) è impostato),<br/>            la stampa è limitata a una rappresentazione a basso livello dell'aspetto, possibilmente di qualità degradata. |

### Vedi anche
* modulo [`aspose.slides.export`](/slides/python-net/it/aspose.slides.export)
* libreria [`Aspose.Slides`](/slides/python-net)
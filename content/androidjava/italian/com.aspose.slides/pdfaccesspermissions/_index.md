---
title: PdfAccessPermissions
second_title: Riferimento API Java di Aspose.Slides per Android
description: Contiene un insieme di flag che specificano quali autorizzazioni di accesso devono essere concesse quando il documento viene aperto con accesso utente.
type: docs
url: /it/com.aspose.slides/pdfaccesspermissions/
---
**Ereditarietà:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Contiene un insieme di flag che specificano quali autorizzazioni di accesso devono essere concesse quando il documento viene aperto con accesso utente.
## Campi

| Campo | Descrizione |
| --- | --- |
| [None](#None) | Specifica che un utente non dispone di autorizzazioni di accesso. |
| [PrintDocument](#PrintDocument) | Specifica se un utente può stampare il documento (potenzialmente non al livello di qualità più alto, a seconda se il bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) è anche impostato). |
| [ModifyContent](#ModifyContent) | Specifica se un utente può modificare il contenuto del documento mediante operazioni diverse da quelle controllate dai bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Specifica se un utente può copiare o estrarre in altro modo testo e grafica dal documento mediante operazioni diverse da quelle controllate dal bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Specifica se un utente può aggiungere o modificare annotazioni di testo, compilare campi di modulo interattivi e, se il bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) è anche impostato, creare o modificare campi di modulo interattivi (inclusi i campi firma). |
| [FillExistingFields](#FillExistingFields) | Specifica se un utente può compilare i campi di modulo interattivi esistenti (inclusi i campi firma), anche se il bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) è disattivato. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Specifica se un utente può estrarre testo e grafica a supporto dell'accessibilità per utenti con disabilità o per altri scopi. |
| [AssembleDocument](#AssembleDocument) | Specifica se un utente può assemblare il documento (inserire, ruotare o eliminare pagine e creare segnalibri o immagini in miniatura), anche se il bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) è disattivato. |
| [HighQualityPrint](#HighQualityPrint) | Specifica se un utente può stampare il documento in una rappresentazione da cui potrebbe essere generata una copia digitale fedele del contenuto PDF. |
### Nessuno {#None}
```
public static final int None
```

Specifica che un utente non dispone di autorizzazioni di accesso.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Specifica se un utente può stampare il documento (potenzialmente non al livello di qualità più alto, a seconda se il bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) è anche impostato).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Specifica se un utente può modificare il contenuto del documento mediante operazioni diverse da quelle controllate dai bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Specifica se un utente può copiare o estrarre in altro modo testo e grafica dal documento mediante operazioni diverse da quelle controllate dal bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Specifica se un utente può aggiungere o modificare annotazioni di testo, compilare campi di modulo interattivi e, se il bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) è anche impostato, creare o modificare campi di modulo interattivi (inclusi i campi firma).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Specifica se un utente può compilare i campi di modulo interattivi esistenti (inclusi i campi firma), anche se il bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) è disattivato.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Specifica se un utente può estrarre testo e grafica a supporto dell'accessibilità per utenti con disabilità o per altri scopi.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Specifica se un utente può assemblare il documento (inserire, ruotare o eliminare pagine e creare segnalibri o immagini in miniatura), anche se il bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) è disattivato.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Specifica se un utente può stampare il documento in una rappresentazione da cui potrebbe essere generata una copia digitale fedele del contenuto PDF. Quando questo bit è disattivato (e il bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) è impostato), la stampa è limitata a una rappresentazione di basso livello dell'aspetto, possibilmente di qualità degradata.
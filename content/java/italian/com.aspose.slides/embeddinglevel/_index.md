---
title: EmbeddingLevel
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta i diritti di licenza per l'incorporamento del font.
type: docs
url: /it/com.aspose.slides/embeddinglevel/
---
**Eredità:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Rappresenta i diritti di licenza per l'incorporamento del font.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Installable](#Installable) | I font con questa impostazione indicano che possono essere incorporati e installati permanentemente sul sistema remoto da un'applicazione. |
| [Restricted](#Restricted) | I font che hanno impostato solo questo bit non devono essere modificati, incorporati o scambiati in alcun modo senza prima ottenere l'autorizzazione del proprietario legale. |
| [PreviewPrint](#PreviewPrint) | Quando questo bit è impostato, il font può essere incorporato e caricato temporaneamente sul sistema remoto. |
| [Editable](#Editable) | Quando questo bit è impostato, il font può essere incorporato ma deve essere installato temporaneamente su altri sistemi. |
| [NoSubsetting](#NoSubsetting) | Quando questo bit è impostato, il font non può essere sottodiviso prima dell'incorporamento. |
| [BitmapOnly](#BitmapOnly) | Quando questo bit è impostato, solo i bitmap contenuti nel font possono essere incorporati. |
### Installabile {#Installable}
```
public static final int Installable
```

I font con questa impostazione indicano che possono essere incorporati e installati permanentemente sul sistema remoto da un'applicazione. L'utente del sistema remoto acquisisce gli stessi diritti, obblighi e licenze per quel font dell'acquirente originale del font, ed è soggetto allo stesso contratto di licenza per l'utente finale, copyright, brevetto di design e/o marchio come l'acquirente originale.

### Limitato {#Restricted}
```
public static final int Restricted
```

I font che hanno impostato solo questo bit non devono essere modificati, incorporati o scambiati in alcun modo senza prima ottenere l'autorizzazione del proprietario legale.

### AnteprimaStampa {#PreviewPrint}
```
public static final int PreviewPrint
```

Quando questo bit è impostato, il font può essere incorporato e caricato temporaneamente sul sistema remoto. I documenti contenenti font Preview & Print devono essere aperti "read-only"; non è possibile apportare modifiche al documento.

### Modificabile {#Editable}
```
public static final int Editable
```

Quando questo bit è impostato, il font può essere incorporato ma deve essere installato temporaneamente su altri sistemi. In contrasto con i font Preview & Print, i documenti contenenti font Editable possono essere aperti per la lettura, è consentita la modifica e le modifiche possono essere salvate.

### NessunaSottodivisione {#NoSubsetting}
```
public static final int NoSubsetting
```

Quando questo bit è impostato, il font non può essere sottodiviso prima dell'incorporamento. Si applicano anche le altre restrizioni di incorporamento specificate nei bit 0-3 e 9.

### SoloBitmap {#BitmapOnly}
```
public static final int BitmapOnly
```

Quando questo bit è impostato, solo i bitmap contenuti nel font possono essere incorporati. Nessun dato di contorno può essere incorporato. Se non ci sono bitmap disponibili nel font, il font è considerato non incorporabile e i servizi di incorporamento falliranno.
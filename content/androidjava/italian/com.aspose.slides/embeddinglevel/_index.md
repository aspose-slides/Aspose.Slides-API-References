---
title: EmbeddingLevel
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta i diritti di licenza per l'incorporamento del font.
type: docs
url: /it/com.aspose.slides/embeddinglevel/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Rappresenta i diritti di licenza per l'incorporamento del font.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Installable](#Installable) | Font con questa impostazione indicano che possono essere incorporati e installati permanentemente sul sistema remoto da un'applicazione. |
| [Restricted](#Restricted) | Font che hanno solo questo bit impostato non devono essere modificati, incorporati o scambiati in alcun modo senza aver prima ottenuto il permesso del proprietario legale. |
| [PreviewPrint](#PreviewPrint) | Quando questo bit è impostato, il font può essere incorporato e caricato temporaneamente sul sistema remoto. |
| [Editable](#Editable) | Quando questo bit è impostato, il font può essere incorporato ma deve essere installato temporaneamente su altri sistemi. |
| [NoSubsetting](#NoSubsetting) | Quando questo bit è impostato, il font non può essere sottoposto a subsetting prima dell'incorporamento. |
| [BitmapOnly](#BitmapOnly) | Quando questo bit è impostato, solo le bitmap contenute nel font possono essere incorporate. |
### Installable {#Installable}
```
public static final int Installable
```

Font con questa impostazione indicano che possono essere incorporati e installati permanentemente sul sistema remoto da un'applicazione. L'utente del sistema remoto acquisisce gli stessi diritti, obblighi e licenze per quel font come l'acquirente originale del font, ed è soggetto allo stesso accordo di licenza per l'utente finale, copyright, brevetto di design e/o marchio come l'acquirente originale.

### Restricted {#Restricted}
```
public static final int Restricted
```

Font che hanno solo questo bit impostato non devono essere modificati, incorporati o scambiati in alcun modo senza aver prima ottenuto il permesso del proprietario legale.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Quando questo bit è impostato, il font può essere incorporato e caricato temporaneamente sul sistema remoto. I documenti contenenti font Preview & Print devono essere aperti "sola lettura"; non è possibile apportare modifiche al documento.

### Editable {#Editable}
```
public static final int Editable
```

Quando questo bit è impostato, il font può essere incorporato ma deve essere installato temporaneamente su altri sistemi. Contrariamente ai font Preview & Print, i documenti contenenti font Editable possono essere aperti per la lettura, la modifica è consentita e le modifiche possono essere salvate.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Quando questo bit è impostato, il font non può essere sottoposto a subsetting prima dell'incorporamento. Altre restrizioni di incorporamento specificate nei bit 0-3 e 9 si applicano anche.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Quando questo bit è impostato, solo le bitmap contenute nel font possono essere incorporate. Nessun dato di contorno può essere incorporato. Se non ci sono bitmap disponibili nel font, allora il font è considerato non incorporabile e i servizi di incorporamento falliranno.
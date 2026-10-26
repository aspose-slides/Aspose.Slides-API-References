---
title: WarningType
second_title: Aspose.Slides für Android via Java API Referenz
description: Stellt einen Typ von Warnung dar.
type: docs
url: /de/com.aspose.slides/warningtype/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Stellt einen Typ von Warnung dar.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Ein Problem wurde im Quelldokument erkannt, wodurch es sehr wahrscheinlich ist, dass das Dokument nicht geöffnet werden kann, wenn es in seinem Originalformat gespeichert wird. |
| [DataLoss](#DataLoss) | Text/Diagramm/Bild oder andere Daten fehlen vollständig entweder im Dokumentbaum nach dem Laden oder im erstellten Dokument nach dem Speichern. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Großer Formatverlust. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Geringer Formatverlust. |
| [CompatibilityIssue](#CompatibilityIssue) | Dies ist ein bekanntes Problem, das das Öffnen des Dokuments durch bestimmte Benutzeragenten oder frühere Versionen von Benutzeragenten verhindert. |
| [UnexpectedContent](#UnexpectedContent) | Einige Inhalte im Quelldokument konnten nicht erkannt werden (d.h. 

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Ein Problem wurde im Quelldokument erkannt, wodurch es sehr wahrscheinlich ist, dass das Dokument nicht geöffnet werden kann, wenn es in seinem Originalformat gespeichert wird.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Text/Diagramm/Bild oder andere Daten fehlen vollständig entweder im Dokumentbaum nach dem Laden oder im erstellten Dokument nach dem Speichern.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Großer Formatverlust.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Geringer Formatverlust.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Dies ist ein bekanntes Problem, das das Öffnen des Dokuments durch bestimmte Benutzeragenten oder frühere Versionen von Benutzeragenten verhindert.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Einige Inhalte im Quelldokument konnten nicht erkannt werden (d.h. werden nicht unterstützt), dies kann zu Problemen führen oder Daten-/Formatverlust zur Folge haben.
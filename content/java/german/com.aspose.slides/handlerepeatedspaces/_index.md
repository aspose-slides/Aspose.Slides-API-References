---
title: HandleRepeatedSpaces
second_title: Aspose.Slides für Java API-Referenz
description: Gibt an, wie wiederholte reguläre Leerzeichen beim Markdown-Export behandelt werden sollen.
type: docs
url: /de/com.aspose.slides/handlerepeatedspaces/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Gibt an, wie wiederholte reguläre Leerzeichen beim Markdown-Export behandelt werden sollen.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [None](#None) | Alle Leerzeichen werden als reguläre Leerzeichen ohne Änderungen beibehalten. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Konvertiert Sequenzen von zwei oder mehr aufeinanderfolgenden regulären Leerzeichen, indem zwischen regulären Leerzeichen und nicht trennbaren Leerzeichen (NBSP) abwechselnd verwendet wird. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Konvertiert Sequenzen von zwei oder mehr aufeinanderfolgenden regulären Leerzeichen, indem das erste Leerzeichen als reguläres Leerzeichen beibehalten und alle nachfolgenden Leerzeichen durch nicht trennbare Leerzeichen (NBSP) ersetzt werden. |
### None {#None}
```
public static final int None
```

Alle Leerzeichen werden als reguläre Leerzeichen ohne Änderungen beibehalten. Es wird keine Transformation angewendet, und mehrere aufeinanderfolgende Leerzeichen werden unverändert exportiert.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Konvertiert Sequenzen von zwei oder mehr aufeinanderfolgenden regulären Leerzeichen, indem zwischen regulären Leerzeichen und nicht trennbaren Leerzeichen (NBSP) abwechselnd verwendet wird. Das erste Leerzeichen bleibt immer als reguläres Leerzeichen erhalten.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Konvertiert Sequenzen von zwei oder mehr aufeinanderfolgenden regulären Leerzeichen, indem das erste Leerzeichen als reguläres Leerzeichen beibehalten und alle nachfolgenden Leerzeichen durch nicht trennbare Leerzeichen (NBSP) ersetzt werden.
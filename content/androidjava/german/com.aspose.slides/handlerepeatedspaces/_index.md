---
title: HandleRepeatedSpaces
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [None](#None) | Alle Leerzeichen werden als reguläre Leerzeichen unverändert beibehalten. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Konvertiert Sequenzen von zwei oder mehr aufeinanderfolgenden regulären Leerzeichen, indem zwischen regulären Leerzeichen und geschützten Leerzeichen (NBSP) abwechselnd verwendet wird. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Konvertiert Sequenzen von zwei oder mehr aufeinanderfolgenden regulären Leerzeichen, indem das erste Leerzeichen als reguläres Leerzeichen beibehalten und alle nachfolgenden Leerzeichen durch geschützte Leerzeichen (NBSP) ersetzt werden. |
### None {#None}
```
public static final int None
```

Alle Leerzeichen werden als reguläre Leerzeichen unverändert beibehalten. Es wird keine Transformation angewendet, und mehrere aufeinanderfolgende Leerzeichen werden unverändert exportiert.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Konvertiert Sequenzen von zwei oder mehr aufeinanderfolgenden regulären Leerzeichen, indem zwischen regulären Leerzeichen und geschützten Leerzeichen (NBSP) abwechselnd verwendet wird. Das erste Leerzeichen wird stets als reguläres Leerzeichen beibehalten.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Konvertiert Sequenzen von zwei oder mehr aufeinanderfolgenden regulären Leerzeichen, indem das erste Leerzeichen als reguläres Leerzeichen beibehalten und alle nachfolgenden Leerzeichen durch geschützte Leerzeichen (NBSP) ersetzt werden.
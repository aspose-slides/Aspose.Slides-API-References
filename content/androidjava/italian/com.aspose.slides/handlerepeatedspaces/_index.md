---
title: HandleRepeatedSpaces
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Specifica come i caratteri di spazio regolari ripetuti devono essere gestiti durante l'esportazione in Markdown.
type: docs
url: /it/com.aspose.slides/handlerepeatedspaces/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Specifica come i caratteri di spazio regolari ripetuti devono essere gestiti durante l'esportazione in Markdown.
## Campi

| Campo | Descrizione |
| --- | --- |
| [None](#None) | Tutti gli spazi sono preservati come caratteri di spazio regolari senza alcuna modifica. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Converte sequenze di due o più spazi regolari consecutivi alternando tra caratteri di spazio regolari e entità di spazio non interrotto NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Converte sequenze di due o più spazi regolari consecutivi preservando il primo spazio come carattere di spazio regolare e sostituendo tutti gli spazi successivi con entità di spazio non interrotto NBSP. |
### None {#None}
```
public static final int None
```


Tutti gli spazi sono preservati come caratteri di spazio regolari senza alcuna modifica. Nessuna trasformazione è applicata e gli spazi consecutivi multipli sono esportati così come sono.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


Converte sequenze di due o più spazi regolari consecutivi alternando tra caratteri di spazio regolari e entità di spazio non interrotto NBSP. Il primo spazio è sempre preservato come spazio regolare.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


Converte sequenze di due o più spazi regolari consecutivi preservando il primo spazio come carattere di spazio regolare e sostituendo tutti gli spazi successivi con entità di spazio non interrotto NBSP.
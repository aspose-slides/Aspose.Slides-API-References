---
title: HandleRepeatedSpaces
second_title: Riferimento API di Aspose.Slides per Java
description: Specifica come gestire i caratteri di spazio regolari ripetuti durante l'esportazione in Markdown.
type: docs
url: /it/com.aspose.slides/handlerepeatedspaces/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Specifica come gestire i caratteri di spazio regolari ripetuti durante l'esportazione in Markdown.
## Campi

| Campo | Descrizione |
| --- | --- |
| [None](#None) | Tutti gli spazi sono conservati come caratteri di spazio regolari senza alcuna modifica. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Converte le sequenze di due o più spazi regolari consecutivi alternando tra caratteri di spazio regolari e entità di spazio non interrompibile NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Converte le sequenze di due o più spazi regolari consecutivi conservando il primo spazio come carattere di spazio regolare e sostituendo tutti gli spazi successivi con entità di spazio non interrompibile NBSP. |
### None {#None}
```
public static final int None
```


Tutti gli spazi sono conservati come caratteri di spazio regolari senza alcuna modifica. Nessuna trasformazione è applicata e gli spazi consecutivi multipli vengono esportati così come sono.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


Converte le sequenze di due o più spazi regolari consecutivi alternando tra caratteri di spazio regolari e entità di spazio non interrompibile NBSP. Il primo spazio è sempre conservato come spazio regolare.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


Converte le sequenze di due o più spazi regolari consecutivi conservando il primo spazio come carattere di spazio regolare e sostituendo tutti gli spazi successivi con entità di spazio non interrompibile NBSP.
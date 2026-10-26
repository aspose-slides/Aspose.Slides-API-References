---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Consente di creare un carattere di raggruppamento matematico
type: docs
url: /it/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Consente di creare un carattere di raggruppamento matematico

--------------------

Per compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Crea un carattere di raggruppamento matematico |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Crea un carattere di raggruppamento matematico |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Crea un carattere di raggruppamento matematico

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare il carattere di raggruppamento |
| character | char | carattere di raggruppamento |
| position | int | posizione del carattere di raggruppamento |
| verticalJustification | int | giustificazione verticale |

**Restituisce:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nuovo elemento di carattere di raggruppamento
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Crea un carattere di raggruppamento matematico

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare il carattere di raggruppamento |

**Restituisce:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nuovo elemento di carattere di raggruppamento
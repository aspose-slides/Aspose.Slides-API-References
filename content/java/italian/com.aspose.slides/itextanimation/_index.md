---
title: ITextAnimation
second_title: Aspose.Slides per Java API Reference
description: Rappresenta l'animazione del testo.
type: docs
url: /it/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Rappresenta l'animazione del testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Aggiunge un nuovo effetto alla fine della sequenza corrente fino alla fine delle animazioni di testo del gruppo. |
| [getBuildType()](#getBuildType--) | Elenco dei tipi di costruzione (per es. |
| [setBuildType(int value)](#setBuildType-int-) | Elenco dei tipi di costruzione (per es. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Effetto forma collegata con gruppo o meno (null) Lettura/scrittura [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Effetto forma collegata con gruppo o meno (null) Lettura/scrittura [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Aggiunge un nuovo effetto alla fine della sequenza corrente fino alla fine delle animazioni di testo del gruppo. Valido solo se il conteggio dei paragrafi di testo è uguale o superiore al conteggio degli effetti di questo gruppo!

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| effectType | int | Tipo di un effetto di animazione [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sottotipi di effetto di animazione [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo di attivazione dell'effetto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - Nuovo oggetto effetto [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Elenco dei tipi di costruzione (per es. Paragrafo 1,2,3, Tutti insieme) dell'animazione del testo. Lettura/scrittura \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Restituisce:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Elenco dei tipi di costruzione (per es. Paragrafo 1,2,3, Tutti insieme) dell'animazione del testo. Lettura/scrittura \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Effetto forma collegata con gruppo o meno (null) Lettura/scrittura [IEffect](../../com.aspose.slides/ieffect).

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Effetto forma collegata con gruppo o meno (null) Lettura/scrittura [IEffect](../../com.aspose.slides/ieffect).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |
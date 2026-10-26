---
title: TextAnimation
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta l'animazione del testo.
type: docs
url: /it/com.aspose.slides/textanimation/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Rappresenta l'animazione del testo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Aggiunge un nuovo effetto alla fine della sequenza corrente fino alla fine delle animazioni di testo di gruppo. |
| [getBuildType()](#getBuildType--) | Elenco dei tipi di costruzione (per es. |
| [setBuildType(int value)](#setBuildType-int-) | Elenco dei tipi di costruzione (per es. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Effetto forma collegata con gruppo o meno (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Effetto forma collegata con gruppo o meno (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

Aggiunge un nuovo effetto alla fine della sequenza corrente fino alla fine delle animazioni di testo di gruppo. Valido solo se il conteggio dei paragrafi di testo è uguale o maggiore del conteggio degli effetti di questo gruppo!

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
public final int getBuildType()
```

Elenco dei tipi di costruzione (per es. Paragrafo 1,2,3, Tutti in una volta) dell'animazione del testo. Lettura/scrittura [BuildType](../../com.aspose.slides/buildtype).

**Restituisce:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

Elenco dei tipi di costruzione (per es. Paragrafo 1,2,3, Tutti in una volta) dell'animazione del testo. Lettura/scrittura [BuildType](../../com.aspose.slides/buildtype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

Effetto forma collegata con gruppo o meno (null). Lettura/scrittura [IEffect](../../com.aspose.slides/ieffect).

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

Effetto forma collegata con gruppo o meno (null). Lettura/scrittura [IEffect](../../com.aspose.slides/ieffect).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |
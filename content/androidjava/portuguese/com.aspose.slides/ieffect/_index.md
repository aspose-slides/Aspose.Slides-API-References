---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Representa efeito de animação.
type: docs
url: /pt/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Representa efeito de animação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getSequence()](#getSequence--) | Retorna uma sequência para um efeito. |
| [getTextAnimation()](#getTextAnimation--) | Retorna animação de texto. |
| [getPresetClassType()](#getPresetClassType--) | Define a classe do efeito. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Define a classe do efeito. |
| [getType()](#getType--) | Define o tipo do efeito. |
| [setType(int value)](#setType-int-) | Define o tipo do efeito. |
| [getSubtype()](#getSubtype--) | Define o subtipo do efeito. |
| [setSubtype(int value)](#setSubtype-int-) | Define o subtipo do efeito. |
| [getBehaviors()](#getBehaviors--) | Retorna a coleção de comportamentos para o efeito. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Retorna a coleção de comportamentos para o efeito. |
| [getTiming()](#getTiming--) | Define o valor de temporização para o efeito. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Define o valor de temporização para o efeito. |
| [getTargetShape()](#getTargetShape--) | Retorna a forma alvo para o efeito. |
| [getSound()](#getSound--) | Define som incorporado para o efeito. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Define som incorporado para o efeito. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Este atributo especifica se o efeito de animação interrompe o som anterior. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Este atributo especifica se o efeito de animação interrompe o som anterior. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Define um tipo de animação posterior para o efeito. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Define um tipo de animação posterior para o efeito. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Define uma cor de animação posterior para o efeito. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Define uma cor de animação posterior para o efeito. |
| [getAnimateTextType()](#getAnimateTextType--) | Define um tipo de animação de texto para o efeito. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Define um tipo de animação de texto para o efeito. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Define um atraso entre partes de texto animado (palavras ou letras). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Define um atraso entre partes de texto animado (palavras ou letras). |

### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

Retorna uma sequência para um efeito. Somente leitura [ISequence](../../com.aspose.slides/isequence).

**Retorna:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

Retorna animação de texto. Somente leitura [ITextAnimation](../../com.aspose.slides/itextanimation).

**Retorna:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

Define a classe do efeito. Leitura/Gravação [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Retorna:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

Define a classe do efeito. Leitura/Gravação [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Define o tipo do efeito. Leitura/Gravação [EffectType](../../com.aspose.slides/effecttype).

**Retorna:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Define o tipo do efeito. Leitura/Gravação [EffectType](../../com.aspose.slides/effecttype).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

Define o subtipo do efeito. Leitura/Gravação [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Retorna:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

Define o subtipo do efeito. Leitura/Gravação [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

Retorna a coleção de comportamentos para o efeito. Leitura/Gravação [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Retorna:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

Retorna a coleção de comportamentos para o efeito. Leitura/Gravação [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Define o valor de temporização para o efeito. Leitura/Gravação [ITiming](../../com.aspose.slides/itiming).

**Retorna:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Define o valor de temporização para o efeito. Leitura/Gravação [ITiming](../../com.aspose.slides/itiming).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

Retorna a forma alvo para o efeito. Somente leitura [IShape](../../com.aspose.slides/ishape).

**Retorna:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Define som incorporado para o efeito. Leitura/Gravação [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtém a sequência de efeitos para o slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrai o som do efeito em um array de bytes
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retorna:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Define som incorporado para o efeito. Leitura/Gravação [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtém a sequência de efeitos para o slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extrai o som do efeito em um array de bytes
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```

Este atributo especifica se o efeito de animação interrompe o som anterior. Leitura/Gravação  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtém o primeiro efeito do primeiro slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Obtém o primeiro efeito do segundo slide.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Altera o segundo efeito Enhancements/Sound para "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retorna:**
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

Este atributo especifica se o efeito de animação interrompe o som anterior. Leitura/Gravação  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtém o primeiro efeito do primeiro slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Obtém o primeiro efeito do segundo slide.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Altera o segundo efeito Enhancements/Sound para "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```

Define um tipo de animação posterior para o efeito. Leitura/Gravação  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtém o primeiro efeito do primeiro slide.
> 
>      // Altera a animação pós-efeito para "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retorna:**
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

Define um tipo de animação posterior para o efeito. Leitura/Gravação  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtém o primeiro efeito do primeiro slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Altera a animação pós-efeito para "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```

Define uma cor de animação posterior para o efeito. Leitura/Gravação [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtém o primeiro efeito do primeiro slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Altera o tipo de animação pós-efeito para "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Define a cor da animação pós-efeito.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

Define uma cor de animação posterior para o efeito. Leitura/Gravação [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Obtém o primeiro efeito do primeiro slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Altera o tipo de animação pós-efeito para "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Define a cor da animação pós-efeito.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```

Define um tipo de animação de texto para o efeito. O texto da forma pode ser animado por letra, por palavra ou tudo de uma vez. Leitura/Gravação  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtém o primeiro efeito do primeiro slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Altera o tipo de animação de texto do efeito para "Por letra"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retorna:**
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

Define um tipo de animação de texto para o efeito. O texto da forma pode ser animado por letra, por palavra ou tudo de uma vez. Leitura/Gravação  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtém o primeiro efeito do primeiro slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Altera o tipo de animação de texto do efeito para "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```

Define um atraso entre partes de texto animado (palavras ou letras). Um valor positivo especifica a porcentagem da duração do efeito. Um valor negativo especifica o atraso em segundos. Leitura/Gravação  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtém o primeiro efeito do primeiro slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Altera o tipo de animação de texto do efeito para "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Define o atraso entre partes de texto animado para 20% da duração do efeito.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retorna:**
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

Define um atraso entre partes de texto animado (palavras ou letras). Um valor positivo especifica a porcentagem da duração do efeito. Um valor negativo especifica o atraso em segundos. Leitura/Gravação  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Obtém o primeiro efeito do primeiro slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Altera o tipo de animação de texto do efeito para "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Define o atraso entre partes de texto animado para 20% da duração do efeito.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
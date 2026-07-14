---
title: Effect
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 애니메이션 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/effect/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject  
```
public class Effect implements IEffect, IDOMObject
```

애니메이션 효과를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSequence()](#getSequence--) | 효과에 대한 시퀀스를 반환합니다. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation 읽기 전용 [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | 효과의 클래스를 정의합니다. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | 효과의 클래스를 정의합니다. |
| [getType()](#getType--) | 효과의 유형을 정의합니다. |
| [setType(int value)](#setType-int-) | 효과의 유형을 정의합니다. |
| [getSubtype()](#getSubtype--) | 효과의 하위 유형을 정의합니다. |
| [setSubtype(int value)](#setSubtype-int-) | 효과의 하위 유형을 정의합니다. |
| [getBehaviors()](#getBehaviors--) | 효과에 대한 동작 컬렉션을 반환합니다. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | 효과에 대한 동작 컬렉션을 반환합니다. |
| [getTiming()](#getTiming--) | 효과의 타이밍 값을 정의합니다. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 효과의 타이밍 값을 정의합니다. |
| [getTargetShape()](#getTargetShape--) | 효과에 대한 대상 셰이프를 반환합니다. |
| [getSound()](#getSound--) | 효과에 대한 내장 사운드를 정의합니다. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 효과에 대한 내장 사운드를 정의합니다. |
| [getStopPreviousSound()](#getStopPreviousSound--) | 이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | 이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다. |
| [getAfterAnimationType()](#getAfterAnimationType--) | 효과에 대한 사후 애니메이션 유형을 정의합니다. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | 효과에 대한 사후 애니메이션 유형을 정의합니다. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | 효과에 대한 사후 애니메이션 색상을 정의합니다. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | 효과에 대한 사후 애니메이션 색상을 정의합니다. |
| [getAnimateTextType()](#getAnimateTextType--) | 효과에 대한 텍스트 애니메이션 유형을 정의합니다. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | 효과에 대한 텍스트 애니메이션 유형을 정의합니다. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | 애니메이션 텍스트 파트(단어나 문자) 사이의 지연을 정의합니다. |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | 애니메이션 텍스트 파트(단어나 문자) 사이의 지연을 정의합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

효과에 대한 시퀀스를 반환합니다. 읽기 전용 [ISequence](../../com.aspose.slides/isequence).

**반환:**  
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation 읽기 전용 [ITextAnimation](../../com.aspose.slides/itextanimation).

**반환:**  
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

효과의 클래스를 정의합니다. 읽기/쓰기 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**반환:**  
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

효과의 클래스를 정의합니다. 읽기/쓰기 [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

효과의 유형을 정의합니다. 읽기/쓰기 [EffectType](../../com.aspose.slides/effecttype).

**반환:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

효과의 유형을 정의합니다. 읽기/쓰기 [EffectType](../../com.aspose.slides/effecttype).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

효과의 하위 유형을 정의합니다. 읽기/쓰기 [EffectSubtype](../../com.aspose.slides/effectsubtype).

**반환:**  
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

효과의 하위 유형을 정의합니다. 읽기/쓰기 [EffectSubtype](../../com.aspose.slides/effectsubtype).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

효과에 대한 동작 컬렉션을 반환합니다. 읽기/쓰기 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**반환:**  
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

효과에 대한 동작 컬렉션을 반환합니다. 읽기/쓰기 [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

효과의 타이밍 값을 정의합니다. 읽기/쓰기 [ITiming](../../com.aspose.slides/itiming).

**반환:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

효과의 타이밍 값을 정의합니다. 읽기/쓰기 [ITiming](../../com.aspose.slides/itiming).

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

효과에 대한 대상 셰이프를 반환합니다. 읽기 전용 [IShape](../../com.aspose.slides/ishape).

**반환:**  
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

효과에 대한 내장 사운드를 정의합니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 슬라이드에 대한 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // 효과 사운드를 바이트 배열로 추출합니다
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

효과에 대한 내장 사운드를 정의합니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 슬라이드에 대한 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // 효과 사운드를 바이트 배열로 추출합니다
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다. 읽기/쓰기 boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 두 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // 두 번째 효과의 Enhancements/Sound를 "Stop Previous Sound"로 변경합니다
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**  
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다. 읽기/쓰기 boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 두 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // 두 번째 효과의 Enhancements/Sound를 "Stop Previous Sound"로 변경합니다
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

효과에 대한 사후 애니메이션 유형을 정의합니다. 읽기/쓰기 [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 효과의 사후 애니메이션을 "Hide on Next Mouse Click"으로 변경합니다
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**  
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

효과에 대한 사후 애니메이션 유형을 정의합니다. 읽기/쓰기 [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 효과의 사후 애니메이션을 "Hide on Next Mouse Click"으로 변경합니다
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

효과에 대한 사후 애니메이션 색상을 정의합니다. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 효과의 사후 애니메이션 유형을 "Color"로 변경합니다
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // 효과의 사후 애니메이션 색상을 설정합니다.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

효과에 대한 사후 애니메이션 색상을 정의합니다. 읽기/쓰기 [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 효과의 사후 애니메이션 유형을 "Color"로 변경합니다
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // 효과의 사후 애니메이션 색상을 설정합니다.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

효과에 대한 텍스트 애니메이션 유형을 정의합니다. 도형 텍스트는 문자별, 단어별 또는 전체 한 번에 애니메이션될 수 있습니다. 읽기/쓰기 AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 효과의 Animate text 유형을 "By letter"로 변경합니다
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**  
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

효과에 대한 텍스트 애니메이션 유형을 정의합니다. 도형 텍스트는 문자별, 단어별 또는 전체 한 번에 애니메이션될 수 있습니다. 읽기/쓰기 AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 효과 Animate text 유형을 "By letter"로 변경합니다
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

애니메이션 텍스트 파트(단어나 문자) 사이의 지연을 정의합니다. 양수 값은 효과 지속 시간의 백분율을 지정하고, 음수 값은 초 단위 지연을 지정합니다. 읽기/쓰기 float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 효과 Animate text 유형을 "By word"로 변경합니다
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // 애니메이션 텍스트 파트 사이의 지연을 효과 지속 시간의 20%로 설정합니다.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**  
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

애니메이션 텍스트 파트(단어나 문자) 사이의 지연을 정의합니다. 양수 값은 효과 지속 시간의 백분율을 지정하고, 음수 값은 초 단위 지연을 지정합니다. 읽기/쓰기 float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // 효과 Animate text 유형을 "By word"로 변경합니다
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // 애니메이션 텍스트 파트 사이의 지연을 효과 지속 시간의 20%로 설정합니다.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**  
com.aspose.slides.IDOMObject
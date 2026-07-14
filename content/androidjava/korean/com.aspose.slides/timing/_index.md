---
title: Timing
second_title: Java API 참조를 이용한 Android용 Aspose.Slides
description: 애니메이션 타이밍을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/timing/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ITiming](../../com.aspose.slides/itiming), com.aspose.slides.IDOMObject
```
public class Timing implements ITiming, IDOMObject
```

애니메이션 타이밍을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | 가속 동작 효과의 지속 시간 비율을 설명합니다. |
| [setAccelerate(float value)](#setAccelerate-float-) | 가속 동작 효과의 지속 시간 비율을 설명합니다. |
| [getDecelerate()](#getDecelerate--) | 감속 동작 효과의 지속 시간 비율을 설명합니다. |
| [setDecelerate(float value)](#setDecelerate-float-) | 감속 동작 효과의 지속 시간 비율을 설명합니다. |
| [getAutoReverse()](#getAutoReverse--) | 전방 방향으로 재생한 후 애니메이션을 역방향으로 자동 재생할지 여부를 설명합니다. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | 전방 방향으로 재생한 후 애니메이션을 역방향으로 자동 재생할지 여부를 설명합니다. |
| [getDuration()](#getDuration--) | 애니메이션 효과의 지속 시간을 설명합니다. |
| [setDuration(float value)](#setDuration-float-) | 애니메이션 효과의 지속 시간을 설명합니다. |
| [getRepeatCount()](#getRepeatCount--) | 효과가 반복되어야 하는 횟수를 설명합니다. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | 효과가 반복되어야 하는 횟수를 설명합니다. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | 이 속성은 효과가 슬라이드가 끝날 때까지 반복될지 여부를 지정합니다. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | 이 속성은 효과가 슬라이드가 끝날 때까지 반복될지 여부를 지정합니다. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | 이 속성은 효과가 다음 클릭 때까지 반복될지 여부를 지정합니다. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | 이 속성은 효과가 다음 클릭 때까지 반복될지 여부를 지정합니다. |
| [getRepeatDuration()](#getRepeatDuration--) | 효과가 반복되어야 하는 횟수를 설명합니다. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | 효과가 반복되어야 하는 횟수를 설명합니다. |
| [getRestart()](#getRestart--) | 효과가 완료된 후 재시작될지 여부를 지정합니다. |
| [setRestart(int value)](#setRestart-int-) | 효과가 완료된 후 재시작될지 여부를 지정합니다. |
| [getRewind()](#getRewind--) | 이 속성은 재생이 끝났을 때 효과를 되감기 할지 여부를 지정합니다. |
| [setRewind(boolean value)](#setRewind-boolean-) | 이 속성은 재생이 끝났을 때 효과를 되감기 할지 여부를 지정합니다. |
| [getSpeed()](#getSpeed--) | 타이밍을 가속(또는 감속)시키는 비율을 지정합니다. |
| [setSpeed(float value)](#setSpeed-float-) | 타이밍을 가속(또는 감속)시키는 비율을 지정합니다. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | 트리거 후 지연 시간을 설명합니다. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | 트리거 후 지연 시간을 설명합니다. |
| [getTriggerType()](#getTriggerType--) | 트리거 유형을 설명합니다. |
| [setTriggerType(int value)](#setTriggerType-int-) | 트리거 유형을 설명합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

가속 동작 효과의 지속 시간 비율을 설명합니다. 읽기/쓰기 float.

**반환:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

가속 동작 효과의 지속 시간 비율을 설명합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

감속 동작 효과의 지속 시간 비율을 설명합니다. 읽기/쓰기 float.

**반환:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

감속 동작 효과의 지속 시간 비율을 설명합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

전방 방향으로 재생한 후 애니메이션을 역방향으로 자동 재생할지 여부를 설명합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

전방 방향으로 재생한 후 애니메이션을 역방향으로 자동 재생할지 여부를 설명합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public final float getDuration()
```

애니메이션 효과의 지속 시간을 설명합니다. 읽기/쓰기 float.

**반환:**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```

애니메이션 효과의 지속 시간을 설명합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```

효과가 반복되어야 하는 횟수를 설명합니다. 읽기/쓰기 float.

**반환:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```

효과가 반복되어야 하는 횟수를 설명합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

이 속성은 효과가 슬라이드가 끝날 때까지 반복될지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드에 대한 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 메인 시퀀스의 첫 번째 효과를 가져옵니다.
>      IEffect effect = effectsSequence.get_Item(0);
>      // 효과의 타이밍/반복을 "Until End of Slide" 로 변경합니다
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public final void setRepeatUntilEndSlide(boolean value)
```

이 속성은 효과가 슬라이드가 끝날 때까지 반복될지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드에 대한 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 메인 시퀀스의 첫 번째 효과를 가져옵니다.
>      IEffect effect = effectsSequence.get_Item(0);
>      // 효과의 타이밍/반복을 "Until End of Slide" 로 변경합니다
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public final boolean getRepeatUntilNextClick()
```

이 속성은 효과가 다음 클릭 때까지 반복될지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드에 대한 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 메인 시퀀스의 첫 번째 효과를 가져옵니다.
>      IEffect effect = effectsSequence.get_Item(0);
>      // 효과의 타이밍/반복을 "Until Next Click" 로 변경합니다
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public final void setRepeatUntilNextClick(boolean value)
```

이 속성은 효과가 다음 클릭 때까지 반복될지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드에 대한 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 메인 시퀀스의 첫 번째 효과를 가져옵니다.
>      IEffect effect = effectsSequence.get_Item(0);
>      // 효과의 타이밍/반복을 "Until Next Click" 로 변경합니다
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public final float getRepeatDuration()
```

효과가 반복되어야 하는 횟수를 설명합니다. 읽기/쓰기 float.

**반환:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```

효과가 반복되어야 하는 횟수를 설명합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

효과가 완료된 후 재시작될지 여부를 지정합니다. 읽기/쓰기 [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**반환:**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

효과가 완료된 후 재시작될지 여부를 지정합니다. 읽기/쓰기 [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

이 속성은 재생이 끝났을 때 효과를 되감기 할지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드에 대한 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 메인 시퀀스의 첫 번째 효과를 가져옵니다.
>      IEffect effect = effectsSequence.get_Item(0);
>      // 효과의 Timing/Rewind 를 켭니다.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public final void setRewind(boolean value)
```

이 속성은 재생이 끝났을 때 효과를 되감기 할지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드에 대한 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 메인 시퀀스의 첫 번째 효과를 가져옵니다.
>      IEffect effect = effectsSequence.get_Item(0);
>      // 효과의 Timing/Rewind 를 켭니다.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSpeed() {#getSpeed--}
```
public final float getSpeed()
```

타이밍을 가속(또는 감속)시키는 비율을 지정합니다. 읽기/쓰기 float.

**반환:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

타이밍을 가속(또는 감속)시키는 비율을 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

트리거 후 지연 시간을 설명합니다. 읽기/쓰기 float.

**반환:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

트리거 후 지연 시간을 설명합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```

트리거 유형을 설명합니다. 읽기/쓰기 [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**반환:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public final void setTriggerType(int value)
```

트리거 유형을 설명합니다. 읽기/쓰기 [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject
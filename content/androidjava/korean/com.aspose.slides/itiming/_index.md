---
title: ITiming
second_title: Aspose.Slides for Android via Java API Reference
description: 애니메이션 타이밍을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itiming/
---```
public interface ITiming
```

애니메이션 타이밍을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | 지속 시간 가속 동작 효과의 백분율을 설명합니다. |
| [setAccelerate(float value)](#setAccelerate-float-) | 지속 시간 가속 동작 효과의 백분율을 설명합니다. |
| [getDecelerate()](#getDecelerate--) | 지속 시간 감속 동작 효과의 백분율을 설명합니다. |
| [setDecelerate(float value)](#setDecelerate-float-) | 지속 시간 감속 동작 효과의 백분율을 설명합니다. |
| [getAutoReverse()](#getAutoReverse--) | 앞 방향으로 재생한 후 애니메이션을 자동으로 역방향으로 재생할지 여부를 설명합니다. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | 앞 방향으로 재생한 후 애니메이션을 자동으로 역방향으로 재생할지 여부를 설명합니다. |
| [getDuration()](#getDuration--) | 애니메이션 효과의 지속 시간을 설명합니다. |
| [setDuration(float value)](#setDuration-float-) | 애니메이션 효과의 지속 시간을 설명합니다. |
| [getRepeatCount()](#getRepeatCount--) | 효과가 반복되어야 하는 횟수를 설명합니다. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | 효과가 반복되어야 하는 횟수를 설명합니다. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | 이 속성은 효과가 슬라이드 끝까지 반복되는지 여부를 지정합니다. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | 이 속성은 효과가 슬라이드 끝까지 반복되는지 여부를 지정합니다. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | 이 속성은 효과가 다음 클릭까지 반복되는지 여부를 지정합니다. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | 이 속성은 효과가 다음 클릭까지 반복되는지 여부를 지정합니다. |
| [getRepeatDuration()](#getRepeatDuration--) | 효과가 반복되어야 하는 횟수를 설명합니다. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | 효과가 반복되어야 하는 횟수를 설명합니다. |
| [getRestart()](#getRestart--) | 효과가 완료된 후 재시작되는지 여부를 지정합니다. |
| [setRestart(int value)](#setRestart-int-) | 효과가 완료된 후 재시작되는지 여부를 지정합니다. |
| [getSpeed()](#getSpeed--) | 타이밍을 가속(또는 감속)시키는 백분율을 지정합니다. |
| [setSpeed(float value)](#setSpeed-float-) | 타이밍을 가속(또는 감속)시키는 백분율을 지정합니다. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | 트리거 후 지연 시간을 설명합니다. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | 트리거 후 지연 시간을 설명합니다. |
| [getTriggerType()](#getTriggerType--) | 트리거 유형을 설명합니다. |
| [setTriggerType(int value)](#setTriggerType-int-) | 트리거 유형을 설명합니다. |
| [getRewind()](#getRewind--) | 이 속성은 재생이 끝난 후 효과를 되감을지 여부를 지정합니다. |
| [setRewind(boolean value)](#setRewind-boolean-) | 이 속성은 재생이 끝난 후 효과를 되감을지 여부를 지정합니다. |

### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

지속 시간 가속 동작 효과의 백분율을 설명합니다. 읽기/쓰기 float.

**반환값:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

지속 시간 가속 동작 효과의 백분율을 설명합니다. 읽기/쓰기 float.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

지속 시간 감속 동작 효과의 백분율을 설명합니다. 읽기/쓰기 float.

**반환값:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

지속 시간 감속 동작 효과의 백분율을 설명합니다. 읽기/쓰기 float.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

앞 방향으로 재생한 후 애니메이션을 자동으로 역방향으로 재생할지 여부를 설명합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

앞 방향으로 재생한 후 애니메이션을 자동으로 역방향으로 재생할지 여부를 설명합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

애니메이션 효과의 지속 시간을 설명합니다. 읽기/쓰기 float.

**반환값:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

애니메이션 효과의 지속 시간을 설명합니다. 읽기/쓰기 float.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

효과가 반복되어야 하는 횟수를 설명합니다. 읽기/쓰기 float.

**반환값:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

효과가 반복되어야 하는 횟수를 설명합니다. 읽기/쓰기 float.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

이 속성은 효과가 슬라이드 끝까지 반복되는지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 메인 시퀀스의 첫 번째 효과를 가져옵니다.
>      IEffect effect = effectsSequence.get_Item(0);
>      // 효과의 타이밍/반복을 "슬라이드 끝까지" 로 변경합니다
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**반환값:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```

이 속성은 효과가 슬라이드 끝까지 반복되는지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 효과 시퀀스를 가져옵니다
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```

이 속성은 효과가 다음 클릭까지 반복되는지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 메인 시퀀스의 첫 번째 효과를 가져옵니다.
>      IEffect effect = effectsSequence.get_Item(0);
>      // 효과의 타이밍/반복을 "Until Next Click" 로 변경합니다
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**반환값:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```

이 속성은 효과가 다음 클릭까지 반복되는지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 효과 시퀀스를 가져옵니다
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```

효과가 반복되어야 하는 횟수를 설명합니다. 읽기/쓰기 float.

**반환값:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

효과가 반복되어야 하는 횟수를 설명합니다. 읽기/쓰기 float.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

효과가 완료된 후 재시작되는지 여부를 지정합니다. 읽기/쓰기 [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**반환값:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

효과가 완료된 후 재시작되는지 여부를 지정합니다. 읽기/쓰기 [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

타이밍을 가속(또는 감속)시키는 백분율을 지정합니다. 읽기/쓰기 float.

**반환값:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

타이밍을 가속(또는 감속)시키는 백분율을 지정합니다. 읽기/쓰기 float.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

트리거 후 지연 시간을 설명합니다. 읽기/쓰기 float.

**반환값:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

트리거 후 지연 시간을 설명합니다. 읽기/쓰기 float.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

트리거 유형을 설명합니다. 읽기/쓰기 [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**반환값:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

트리거 유형을 설명합니다. 읽기/쓰기 [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

이 속성은 재생이 끝난 후 효과를 되감을지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 메인 시퀀스의 첫 번째 효과를 가져옵니다.
>      IEffect effect = effectsSequence.get_Item(0);
>      // 효과의 타이밍/리와인드를 켭니다.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환값:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```

이 속성은 재생이 끝난 후 효과를 되감을지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드의 효과 시퀀스를 가져옵니다
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // 메인 시퀀스의 첫 번째 효과를 가져옵니다.
>      IEffect effect = effectsSequence.get_Item(0);
>      // 효과의 타이밍/리와인드를 켭니다.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
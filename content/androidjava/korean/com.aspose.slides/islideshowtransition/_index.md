---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Represents slide show transition.
type: docs
url: /ko/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

슬라이드 쇼 전환을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSound()](#getSound--) | 내장 오디오 데이터를 반환하거나 설정합니다. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 내장 오디오 데이터를 반환하거나 설정합니다. |
| [getSoundMode()](#getSoundMode--) | 슬라이드 전환에 대한 사운드 모드를 설정하거나 반환합니다. |
| [setSoundMode(int value)](#setSoundMode-int-) | 슬라이드 전환에 대한 사운드 모드를 설정하거나 반환합니다. |
| [getSoundLoop()](#getSoundLoop--) | 이 속성은 사운드가 슬라이드 쇼에서 다음 사운드 이벤트가 발생할 때까지 반복되는지 여부를 지정합니다. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | 이 속성은 사운드가 슬라이드 쇼에서 다음 사운드 이벤트가 발생할 때까지 반복되는지 여부를 지정합니다. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | 마우스 클릭이 슬라이드를 진행시킬지 여부를 지정합니다. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | 마우스 클릭이 슬라이드를 진행시킬지 여부를 지정합니다. |
| [getAdvanceAfter()](#getAdvanceAfter--) | 이 속성은 슬라이드 쇼가 일정 시간 후 다음 슬라이드로 넘어갈지 여부를 지정합니다. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | 이 속성은 슬라이드 쇼가 일정 시간 후 다음 슬라이드로 넘어갈지 여부를 지정합니다. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | 전환이 시작되어야 하는 시간(밀리초)을 지정합니다. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | 전환이 시작되어야 하는 시간(밀리초)을 지정합니다. |
| [getSpeed()](#getSpeed--) | 현재 슬라이드에서 다음 슬라이드로 전환할 때 사용할 전환 속도를 지정합니다. |
| [setSpeed(int value)](#setSpeed-int-) | 현재 슬라이드에서 다음 슬라이드로 전환할 때 사용할 전환 속도를 지정합니다. |
| [getValue()](#getValue--) | 슬라이드 쇼 전환 값. |
| [getType()](#getType--) | 전환 유형. |
| [setType(int value)](#setType-int-) | 전환 유형. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | 이 사운드가 내장 사운드인지 여부를 지정합니다. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | 이 사운드가 내장 사운드인지 여부를 지정합니다. |
| [getSoundName()](#getSoundName--) | 전환 사운드에 대한 사람이 읽을 수 있는 이름을 지정합니다. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | 전환 사운드에 대한 사람이 읽을 수 있는 이름을 지정합니다. |
| [getDuration()](#getDuration--) | 슬라이드 전환 효과의 지속 시간을 밀리초 단위로 가져오거나 설정합니다. |
| [setDuration(int value)](#setDuration-int-) | 슬라이드 전환 효과의 지속 시간을 밀리초 단위로 가져오거나 설정합니다. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

내장 오디오 데이터를 반환하거나 설정합니다. 읽기-쓰기 [IAudio](../../com.aspose.slides/iaudio).

**반환값:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

내장 오디오 데이터를 반환하거나 설정합니다. 읽기-쓰기 [IAudio](../../com.aspose.slides/iaudio).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

슬라이드 전환에 대한 사운드 모드를 설정하거나 반환합니다. 읽기-쓰기 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**반환값:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

슬라이드 전환에 대한 사운드 모드를 설정하거나 반환합니다. 읽기-쓰기 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

이 속성은 사운드가 슬라이드 쇼에서 다음 사운드 이벤트가 발생할 때까지 반복되는지 여부를 지정합니다. 읽기-쓰기 boolean.

**반환값:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

이 속성은 사운드가 슬라이드 쇼에서 다음 사운드 이벤트가 발생할 때까지 반복되는지 여부를 지정합니다. 읽기-쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

마우스 클릭이 슬라이드를 진행시킬지 여부를 지정합니다. 이 속성이 지정되지 않으면 true 값이 기본값으로 가정됩니다. 읽기-쓰기 boolean.

**반환값:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

마우스 클릭이 슬라이드를 진행시킬지 여부를 지정합니다. 이 속성이 지정되지 않으면 true 값이 기본값으로 가정됩니다. 읽기-쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

이 속성은 슬라이드 쇼가 일정 시간 후 다음 슬라이드로 넘어갈지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드 전환을 가져옵니다
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Advance Slide After 플래그가 체크되어 있는지 확인합니다
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time 값을 가져옵니다
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

이 속성은 슬라이드 쇼가 일정 시간 후 다음 슬라이드로 넘어갈지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 첫 번째 슬라이드 전환을 가져옵니다
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Advance Slide After 플래그가 체크되었는지 확인합니다
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Advance Slide After Time 값을 가져옵니다
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

전환이 시작되어야 하는 시간(밀리초)을 지정합니다. 이 설정은 advClick 속성과 함께 사용할 수 있습니다. 이 속성이 지정되지 않으면 자동 진행이 발생하지 않는 것으로 가정됩니다. 읽기-쓰기 long.

**반환값:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

전환이 시작되어야 하는 시간(밀리초)을 지정합니다. 이 설정은 advClick 속성과 함께 사용할 수 있습니다. 이 속성이 지정되지 않으면 자동 진행이 발생하지 않는 것으로 가정됩니다. 읽기-쓰기 long.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

현재 슬라이드에서 다음 슬라이드로 전환할 때 사용할 전환 속도를 지정합니다. 읽기-쓰기 [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**반환값:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

현재 슬라이드에서 다음 슬라이드로 전환할 때 사용할 전환 속도를 지정합니다. 읽기-쓰기 [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

슬라이드 쇼 전환 값. 읽기 전용 [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**반환값:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

전환 유형. 읽기-쓰기 [TransitionType](../../com.aspose.slides/transitiontype).

**반환값:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

전환 유형. 읽기-쓰기 [TransitionType](../../com.aspose.slides/transitiontype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

이 사운드가 내장 사운드인지 여부를 지정합니다. 이 속성이 true로 설정되면 생성 애플리케이션은 해당 사운드가 내장 사운드 목록에 지정된 name 속성을 확인하도록 알림을 받고, 필요에 따라 사용자 정의 이름이나 UI를 표시할 수 있습니다. 읽기-쓰기 boolean.

**반환값:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

이 사운드가 내장 사운드인지 여부를 지정합니다. 이 속성이 true로 설정되면 생성 애플리케이션은 해당 사운드가 내장 사운드 목록에 지정된 name 속성을 확인하도록 알림을 받고, 필요에 따라 사용자 정의 이름이나 UI를 표시할 수 있습니다. 읽기-쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

전환 사운드에 대한 사람이 읽을 수 있는 이름을 지정합니다. (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) 속성을 할당하여 사운드 이름을 가져오거나 설정해야 합니다. 읽기-쓰기 String.

**반환값:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

전환 사운드에 대한 사람이 읽을 수 있는 이름을 지정합니다. \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) 속성을 할당하여 사운드 이름을 가져오거나 설정해야 합니다. 읽기-쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

슬라이드 전환 효과의 지속 시간을 밀리초 단위로 가져오거나 설정합니다. 읽기/쓰기 int.

PresentationML 스키마의 p:transition 요소에 있는 p14:dur 속성에 해당합니다. 설정되지 않은 경우, 지속 시간은 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 속성과 전환 유형을 기반으로 자동으로 결정됩니다.

**반환값:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

슬라이드 전환 효과의 지속 시간을 밀리초 단위로 가져오거나 설정합니다. 읽기/쓰기 int.

PresentationML 스키마의 p:transition 요소에 있는 p14:dur 속성에 해당합니다. 설정되지 않은 경우, 지속 시간은 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 속성과 전환 유형을 기반으로 자동으로 결정됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
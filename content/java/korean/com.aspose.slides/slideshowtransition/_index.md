---
title: SlideShowTransition
second_title: Aspose.Slides for Java API 참조
description: 슬라이드 쇼 전환을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/slideshowtransition/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)  
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

슬라이드 쇼 전환을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSound()](#getSound--) | 내장된 오디오 데이터를 반환하거나 설정합니다. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 내장된 오디오 데이터를 반환하거나 설정합니다. |
| [getSoundMode()](#getSoundMode--) | 슬라이드 전환을 위한 사운드 모드를 설정하거나 반환합니다. |
| [setSoundMode(int value)](#setSoundMode-int-) | 슬라이드 전환을 위한 사운드 모드를 설정하거나 반환합니다. |
| [getSoundLoop()](#getSoundLoop--) | 이 속성은 사운드가 슬라이드쇼에서 다음 사운드 이벤트가 발생할 때까지 반복될지 여부를 지정합니다. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | 이 속성은 사운드가 슬라이드쇼에서 다음 사운드 이벤트가 발생할 때까지 반복될지 여부를 지정합니다. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | 마우스 클릭으로 슬라이드를 전환할지 여부를 지정합니다. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | 마우스 클릭으로 슬라이드를 전환할지 여부를 지정합니다. |
| [getAdvanceAfter()](#getAdvanceAfter--) | 이 속성은 일정 시간 후에 슬라이드쇼가 다음 슬라이드로 이동할지 여부를 지정합니다. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | 이 속성은 일정 시간 후에 슬라이드쇼가 다음 슬라이드로 이동할지 여부를 지정합니다. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | 전환이 시작될 시간을 밀리초 단위로 지정합니다. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | 전환이 시작될 시간을 밀리초 단위로 지정합니다. |
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
| [equals(Object obj)](#equals-java.lang.Object-) | 두 SlideShowTransition 인스턴스가 동일한지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 해시 테이블과 같은 해시 알고리즘 및 데이터 구조에서 사용할 수 있는 특정 유형에 대한 해시 함수 역할을 합니다. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

내장된 오디오 데이터를 반환하거나 설정합니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

**반환값:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

내장된 오디오 데이터를 반환하거나 설정합니다. 읽기/쓰기 [IAudio](../../com.aspose.slides/iaudio).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

슬라이드 전환을 위한 사운드 모드를 설정하거나 반환합니다. 읽기/쓰기 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**반환값:**  
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

슬라이드 전환을 위한 사운드 모드를 설정하거나 반환합니다. 읽기/쓰기 [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

이 속성은 사운드가 슬라이드쇼에서 다음 사운드 이벤트가 발생할 때까지 반복될지 여부를 지정합니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

이 속성은 사운드가 슬라이드쇼에서 다음 사운드 이벤트가 발생할 때까지 반복될지 여부를 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

마우스 클릭으로 슬라이드를 전환할지 여부를 지정합니다. 이 속성이 지정되지 않은 경우 true 값이 기본으로 가정됩니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

마우스 클릭으로 슬라이드를 전환할지 여부를 지정합니다. 이 속성이 지정되지 않은 경우 true 값이 기본으로 가정됩니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

이 속성은 일정 시간 후에 슬라이드쇼가 다음 슬라이드로 이동할지 여부를 지정합니다. 읽기/쓰기 boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Get the first slide Transition
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Check if the Advance Slide After flag is checked
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Get the Advance Slide After Time value
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
public final void setAdvanceAfter(boolean value)
```

이 속성은 일정 시간 후에 슬라이드쇼가 다음 슬라이드로 이동할지 여부를 지정합니다. 읽기/쓰기 boolean.

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
public final long getAdvanceAfterTime()
```

전환이 시작될 시간을 밀리초 단위로 지정합니다. 이 설정은 advClick 속성과 함께 사용할 수 있습니다. 이 속성이 지정되지 않은 경우 자동 전환이 발생하지 않는다고 가정합니다. 읽기/쓰기 long.

**반환값:**  
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

전환이 시작될 시간을 밀리초 단위로 지정합니다. 이 설정은 advClick 속성과 함께 사용할 수 있습니다. 이 속성이 지정되지 않은 경우 자동 전환이 발생하지 않는다고 가정합니다. 읽기/쓰기 long.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

현재 슬라이드에서 다음 슬라이드로 전환할 때 사용할 전환 속도를 지정합니다. 읽기/쓰기 [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**반환값:**  
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

현재 슬라이드에서 다음 슬라이드로 전환할 때 사용할 전환 속도를 지정합니다. 읽기/쓰기 [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

슬라이드 쇼 전환 값. 읽기 전용 [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**반환값:**  
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

전환 유형. 읽기/쓰기 [TransitionType](../../com.aspose.slides/transitiontype).

**반환값:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

전환 유형. 읽기/쓰기 [TransitionType](../../com.aspose.slides/transitiontype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

이 사운드가 내장 사운드인지 여부를 지정합니다. 이 속성이 true 로 설정되면 생성 애플리케이션은 내장 사운드 목록에서 지정된 name 속성을 확인하고 필요에 따라 사용자 지정 이름이나 UI를 표시하도록 알립니다. 읽기/쓰기 boolean.

**반환값:**  
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

이 사운드가 내장 사운드인지 여부를 지정합니다. 이 속성이 true 로 설정되면 생성 애플리케이션은 내장 사운드 목록에서 지정된 name 속성을 확인하고 필요에 따라 사용자 지정 이름이나 UI를 표시하도록 알립니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

전환 사운드에 대한 사람이 읽을 수 있는 이름을 지정합니다. Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) 속성을 할당해야 이름을 가져오거나 설정할 수 있습니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

전환 사운드에 대한 사람이 읽을 수 있는 이름을 지정합니다. Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) 속성을 할당해야 이름을 가져오거나 설정할 수 있습니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

슬라이드 전환 효과의 지속 시간을 밀리초 단위로 가져오거나 설정합니다. 읽기/쓰기 int.

--------------------

PresentationML 스키마의 p:transition 요소에 있는 p14:dur 속성에 해당합니다. 설정되지 않은 경우 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 속성과 전환 유형에 따라 자동으로 지속 시간이 결정됩니다.

**반환값:**  
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

슬라이드 전환 효과의 지속 시간을 밀리초 단위로 가져오거나 설정합니다. 읽기/쓰기 int.

--------------------

PresentationML 스키마의 p:transition 요소에 있는 p14:dur 속성에 해당합니다. 설정되지 않은 경우 \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) 속성과 전환 유형에 따라 자동으로 지속 시간이 결정됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

두 SlideShowTransition 인스턴스가 동일한지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 현재 SlideShowTransition와 비교할 SlideShowTransition. |

**반환값:**  
boolean -  **true**  if the specified SlideShowTransition is equal to the current SlideShowTransition; otherwise,  **false** .

### hashCode() {#hashCode--}
```
public int hashCode()
```

해시 테이블과 같은 해시 알고리즘 및 데이터 구조에서 사용할 수 있는 특정 유형에 대한 해시 함수 역할을 합니다.

**반환값:**  
int - 23454

--------------------

컴파일러를 만족시키기 위해 재정의되었습니다. 객체가 변경 가능하므로 항상 상수 값을 반환합니다.
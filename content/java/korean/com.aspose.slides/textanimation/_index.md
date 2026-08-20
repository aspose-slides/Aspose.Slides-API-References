---
title: TextAnimation
second_title: Aspose.Slides Java API 참조
description: 텍스트 애니메이션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/textanimation/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

텍스트 애니메이션을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 새 효과를 현재 시퀀스의 끝에 추가하여 그룹 텍스트 애니메이션의 끝에 배치합니다. |
| [getBuildType()](#getBuildType--) | 빌드 유형 목록 (예시 |
| [setBuildType(int value)](#setBuildType-int-) | 빌드 유형 목록 (예시 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | 그룹 여부에 따라 연결된 모양 효과 (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | 그룹 여부에 따라 연결된 모양 효과 (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


새 효과를 현재 시퀀스의 끝에 추가하여 그룹 텍스트 애니메이션의 끝에 배치합니다. 이 효과는 텍스트 단락 수가 이 그룹의 효과 수와 같거나 더 많을 때만 유효합니다!

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| effectType | int | 애니메이션 효과의 유형 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 애니메이션 효과의 하위 유형 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 효과의 트리거 유형 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**반환값:**
[IEffect](../../com.aspose.slides/ieffect) - 새 효과 객체 [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


텍스트 애니메이션의 빌드 유형 목록 (예: 단락 1,2,3, 한 번에 모두). 읽기/쓰기 [BuildType](../../com.aspose.slides/buildtype).

**반환값:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


텍스트 애니메이션의 빌드 유형 목록 (예: 단락 1,2,3, 한 번에 모두). 읽기/쓰기 [BuildType](../../com.aspose.slides/buildtype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


그룹 여부에 따라 연결된 모양 효과 (null). 읽기/쓰기 [IEffect](../../com.aspose.slides/ieffect).

**반환값:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


그룹 여부에 따라 연결된 모양 효과 (null). 읽기/쓰기 [IEffect](../../com.aspose.slides/ieffect).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |
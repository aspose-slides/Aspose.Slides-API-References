---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: Represent text animation.
type: docs
url: /ko/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

텍스트 애니메이션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 현재 시퀀스의 끝에 새 효과를 추가하여 그룹 텍스트 애니메이션의 끝에 배치합니다. |
| [getBuildType()](#getBuildType--) | 빌드 유형 목록 (예시 용 |
| [setBuildType(int value)](#setBuildType-int-) | 빌드 유형 목록 (예시 용 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | 그룹과 연결된 형태 효과 또는 연결되지 않은 경우(null) 읽기/쓰기 [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | 그룹과 연결된 형태 효과 또는 연결되지 않은 경우(null) 읽기/쓰기 [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

현재 시퀀스의 끝에 새 효과를 추가하여 그룹 텍스트 애니메이션의 끝에 배치합니다. 이 그룹의 효과 개수보다 텍스트 단락 수가 같거나 더 많을 때만 유효합니다!

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| effectType | int | 애니메이션 효과 유형 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 애니메이션 효과의 하위 유형 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 효과의 트리거 유형 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**반환값:**
[IEffect](../../com.aspose.slides/ieffect) - 새 효과 객체 [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

텍스트 애니메이션의 빌드 유형 목록 (예: Paragraph 1,2,3, All at Once). 읽기/쓰기 \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**반환값:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

텍스트 애니메이션의 빌드 유형 목록 (예: Paragraph 1,2,3, All at Once). 읽기/쓰기 \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

그룹과 연결된 형태 효과 또는 연결되지 않은 경우(null) 읽기/쓰기 [IEffect](../../com.aspose.slides/ieffect).

**반환값:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

그룹과 연결된 형태 효과 또는 연결되지 않은 경우(null) 읽기/쓰기 [IEffect](../../com.aspose.slides/ieffect).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |
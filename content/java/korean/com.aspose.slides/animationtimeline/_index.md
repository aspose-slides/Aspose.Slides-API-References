---
title: AnimationTimeLine
second_title: Aspose.Slides Java API 레퍼런스
description: 애니메이션의 타임라인을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/animationtimeline/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)  
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

애니메이션의 타임라인을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | 대화형 시퀀스 컬렉션을 반환합니다. |
| [getMainSequence()](#getMainSequence--) | 주 효과 컬렉션만 포함할 수 있는 주요 시퀀스를 반환합니다. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | 텍스트 애니메이션 컬렉션을 반환합니다. |

### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

대화형 시퀀스 컬렉션을 반환합니다. 이 시퀀스는 지정된 대상 도형을 클릭하여 발생하는 효과만 포함할 수 있습니다. 읽기 전용 [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**반환:**  
[ISequenceCollection](../../com.aspose.slides/isequencecollection)

### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

주 효과 컬렉션만 포함할 수 있는 주요 시퀀스를 반환합니다. 읽기 전용 [ISequence](../../com.aspose.slides/isequence).

**반환:**  
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

텍스트 애니메이션 컬렉션을 반환합니다. 읽기 전용 [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**반환:**  
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
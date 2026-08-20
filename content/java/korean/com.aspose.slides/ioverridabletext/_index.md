---
title: IOverridableText
second_title: Aspose.Slides for Java API 참조
description: 차트에 대한 재정의 가능한 텍스트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ioverridabletext/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

차트에 대한 재정의 가능한 텍스트를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 풍부한 서식이 적용된 텍스트를 포함할 수 있습니다. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 매개변수 "text"의 텍스트로 TextFrameForOverriding을 초기화합니다. |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


풍부한 서식이 적용된 텍스트를 포함할 수 있습니다. 이 속성이 null이 아니면 이 서식이 적용된 텍스트 값이 자동 생성된 텍스트를 대체합니다. 자동 생성된 텍스트는 데이터 레이블, 값 축의 표시 단위 레이블, 축 제목, 차트 제목, 트렌드라인 레이블의 암시적 속성입니다. 자동 생성된 텍스트는 IFormattedTextContainer.TextFormat 속성으로 서식이 지정됩니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환값:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


매개변수 "text"의 텍스트로 TextFrameForOverriding을 초기화합니다. TextFrameForOverriding이 이미 초기화된 경우 단순히 해당 텍스트를 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 새 TextFrameForOverriding의 텍스트. |

**반환값:**
[ITextFrame](../../com.aspose.slides/itextframe) - 텍스트 프레임 [ITextFrame](../../com.aspose.slides/itextframe)
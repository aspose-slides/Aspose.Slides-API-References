---
title: IOverridableText
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 차트에 대한 재정의 가능한 텍스트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ioverridabletext/
---
**전체 구현된 인터페이스:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

차트에 대한 재정의 가능한 텍스트를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 리치 서식 텍스트를 포함할 수 있습니다. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 파라미터 "text"의 텍스트로 TextFrameForOverriding을 초기화합니다. |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

리치 서식 텍스트를 포함할 수 있습니다. 이 속성이 null이 아니면 이 서식이 적용된 텍스트 값이 자동 생성된 텍스트를 덮어씁니다. 자동 생성된 텍스트는 데이터 레이블, 값 축의 표시 단위 레이블, 축 제목, 차트 제목, 추세선 레이블의 암시적 속성입니다. 자동 생성된 텍스트는 IFormattedTextContainer.TextFormat 속성을 사용해 서식이 지정됩니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

파라미터 "text"의 텍스트로 TextFrameForOverriding을 초기화합니다. TextFrameForOverriding이 이미 초기화된 경우 텍스트를 간단히 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 새 TextFrameForOverriding에 대한 텍스트입니다. |

**반환:**
[ITextFrame](../../com.aspose.slides/itextframe) - 텍스트 프레임 [ITextFrame](../../com.aspose.slides/itextframe)
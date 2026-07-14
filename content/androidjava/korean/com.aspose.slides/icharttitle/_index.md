---
title: IChartTitle
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 차트 제목 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icharttitle/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

차트 제목 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOverlay()](#getOverlay--) | 다른 차트 요소가 제목과 겹치도록 허용할지를 판단합니다. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 다른 차트 요소가 제목과 겹치도록 허용할지를 판단합니다. |
| [getFormat()](#getFormat--) | 제목의 채우기, 선, 효과 스타일을 반환합니다. |

### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

다른 차트 요소가 제목과 겹치도록 허용할지를 판단합니다. 읽기/쓰기 부울.

**반환:**
boolean

### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

다른 차트 요소가 제목과 겹치도록 허용할지를 판단합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

제목의 채우기, 선, 효과 스타일을 반환합니다. 읽기 전용 [IFormat](../../com.aspose.slides/iformat).

**반환:**
[IFormat](../../com.aspose.slides/iformat)
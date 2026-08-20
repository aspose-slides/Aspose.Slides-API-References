---
title: SvgEvent
second_title: Aspose.Slides Java API 레퍼런스
description: SVG 모양에 대한 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/svgevent/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SvgEvent extends System.Enum
```

SVG 모양에 대한 옵션을 나타냅니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [OnFocusIn](#OnFocusIn) | 요소가 포커스를 받을 때 발생합니다. 예를 들어 텍스트가 선택될 때와 같습니다. |
| [OnFocusOut](#OnFocusOut) | 요소가 포커스를 잃을 때 발생합니다. 예를 들어 텍스트 선택이 해제될 때와 같습니다. |
| [OnActivate](#OnActivate) | 요소가 활성화될 때 발생합니다. 예를 들어 마우스 클릭이나 키 입력을 통해 활성화될 때와 같습니다. |
| [OnClick](#OnClick) | 포인팅 장치 버튼을 요소 위에서 클릭할 때 발생합니다. |
| [OnMouseDown](#OnMouseDown) | 포인팅 장치 버튼을 요소 위에서 누를 때 발생합니다. |
| [OnMouseUp](#OnMouseUp) | 포인팅 장치 버튼을 요소 위에서 놓을 때 발생합니다. |
| [OnMouseOver](#OnMouseOver) | 포인팅 장치가 요소 위로 이동할 때 발생합니다. |
| [OnMouseMove](#OnMouseMove) | 포인팅 장치가 요소 위에 있는 동안 이동할 때 발생합니다. |
| [OnMouseOut](#OnMouseOut) | 포인팅 장치가 요소에서 멀어질 때 발생합니다. |
| [OnLoad](#OnLoad) | 사용자 에이전트가 요소와 그 하위 요소 및 렌더링에 필요한 모든 참조된 리소스를 완전히 파싱했을 때 발생합니다. |
| [OnUnload](#OnUnload) | DOM 구현이 문서를 창이나 프레임에서 제거할 때 발생합니다. |
| [OnAbort](#OnAbort) | 요소가 완전히 로드되기 전에 페이지 로딩이 중단될 때 발생합니다. |
| [OnError](#OnError) | 요소가 제대로 로드되지 않거나 스크립트 실행 중 오류가 발생할 때 발생합니다. |
| [OnResize](#OnResize) | 문서 뷰가 크기 조정될 때 발생합니다. 최상위 svg 요소에만 적용됩니다. |
| [OnScroll](#OnScroll) | 문서 뷰가 X축, Y축 또는 두 축을 따라 이동될 때 발생합니다. 최상위 svg 요소에만 적용됩니다. |
| [OnZoom](#OnZoom) | 문서 뷰의 줌 레벨이 변경될 때 발생합니다. 최상위 svg 요소에만 적용됩니다. |
| [OnBegin](#OnBegin) | 애니메이션 요소가 시작될 때 발생합니다. |
| [OnEnd](#OnEnd) | 애니메이션 요소가 끝날 때 발생합니다. |
| [OnRepeat](#OnRepeat) | 애니메이션 요소가 반복될 때 발생합니다. |
### OnFocusIn {#OnFocusIn}
```
public static final int OnFocusIn
```

요소가 포커스를 받을 때 발생합니다. 예를 들어 텍스트가 선택될 때와 같습니다.

### OnFocusOut {#OnFocusOut}
```
public static final int OnFocusOut
```

요소가 포커스를 잃을 때 발생합니다. 예를 들어 텍스트 선택이 해제될 때와 같습니다.

### OnActivate {#OnActivate}
```
public static final int OnActivate
```

요소가 활성화될 때 발생합니다. 예를 들어 마우스 클릭이나 키 입력을 통해 활성화될 때와 같습니다.

### OnClick {#OnClick}
```
public static final int OnClick
```

포인팅 장치 버튼을 요소 위에서 클릭할 때 발생합니다.

### OnMouseDown {#OnMouseDown}
```
public static final int OnMouseDown
```

포인팅 장치 버튼을 요소 위에서 누를 때 발생합니다.

### OnMouseUp {#OnMouseUp}
```
public static final int OnMouseUp
```

포인팅 장치 버튼을 요소 위에서 놓을 때 발생합니다.

### OnMouseOver {#OnMouseOver}
```
public static final int OnMouseOver
```

포인팅 장치가 요소 위로 이동할 때 발생합니다.

### OnMouseMove {#OnMouseMove}
```
public static final int OnMouseMove
```

포인팅 장치가 요소 위에 있는 동안 이동할 때 발생합니다.

### OnMouseOut {#OnMouseOut}
```
public static final int OnMouseOut
```

포인팅 장치가 요소에서 멀어질 때 발생합니다.

### OnLoad {#OnLoad}
```
public static final int OnLoad
```

사용자 에이전트가 요소와 그 하위 요소 및 렌더링에 필요한 모든 참조된 리소스를 완전히 파싱했을 때 발생합니다.

### OnUnload {#OnUnload}
```
public static final int OnUnload
```

DOM 구현이 문서를 창이나 프레임에서 제거할 때 발생합니다. Only applicable to outermost svg elements.

### OnAbort {#OnAbort}
```
public static final int OnAbort
```

페이지 로딩이 요소가 완전히 로드되기 전에 중단될 때 발생합니다.

### OnError {#OnError}
```
public static final int OnError
```

요소가 제대로 로드되지 않거나 스크립트 실행 중 오류가 발생할 때 발생합니다.

### OnResize {#OnResize}
```
public static final int OnResize
```

문서 뷰가 크기 조정될 때 발생합니다. 최상위 svg 요소에만 적용됩니다.

### OnScroll {#OnScroll}
```
public static final int OnScroll
```

문서 뷰가 X축, Y축 또는 두 축을 따라 이동될 때 발생합니다. 최상위 svg 요소에만 적용됩니다.

### OnZoom {#OnZoom}
```
public static final int OnZoom
```

문서 뷰의 줌 레벨이 변경될 때 발생합니다. 최상위 svg 요소에만 적용됩니다.

### OnBegin {#OnBegin}
```
public static final int OnBegin
```

애니메이션 요소가 시작될 때 발생합니다.

### OnEnd {#OnEnd}
```
public static final int OnEnd
```

애니메이션 요소가 끝날 때 발생합니다.

### OnRepeat {#OnRepeat}
```
public static final int OnRepeat
```

애니메이션 요소가 반복될 때 발생합니다.
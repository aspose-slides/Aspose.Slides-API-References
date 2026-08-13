---
title: SvgEvent
second_title: Aspose.Slides for C++ API 참조
description: SVG 모양에 대한 옵션을 나타냅니다.
type: docs
weight: 1067
url: /ko/aspose.slides.export/svgevent/
---
## SvgEvent 열거형

SVG 모양에 대한 옵션을 나타냅니다.

```cpp
enum class SvgEvent
```

### 값

| Name | Value | Description |
| --- | --- | --- |
| OnFocusIn | 0 | 요소가 포커스를 받을 때 발생합니다. 예를 들어 텍스트가 선택될 때와 같습니다. |
| OnFocusOut | 1 | 요소가 포커스를 잃을 때 발생합니다. 예를 들어 텍스트의 선택이 해제될 때와 같습니다. |
| OnActivate | 2 | 요소가 활성화될 때 발생합니다. 예를 들어 마우스 클릭이나 키 입력을 통해 활성화될 때와 같습니다. |
| OnClick | 3 | 포인팅 장치 버튼이 요소 위에서 클릭될 때 발생합니다. |
| OnMouseDown | 4 | 포인팅 장치 버튼이 요소 위에서 눌릴 때 발생합니다. |
| OnMouseUp | 5 | 포인팅 장치 버튼이 요소 위에서 놓일 때 발생합니다. |
| OnMouseOver | 6 | 포인팅 장치가 요소 위로 이동할 때 발생합니다. |
| OnMouseMove | 7 | 포인팅 장치가 요소 위에 있는 동안 이동할 때 발생합니다. |
| OnMouseOut | 8 | 포인팅 장치가 요소에서 벗어날 때 발생합니다. |
| OnLoad | 9 | 사용자 에이전트가 요소와 그 하위 요소 및 렌더링에 필요한 모든 참조된 리소스를 완전히 파싱했을 때 발생합니다. |
| OnUnload | 10 | [DOM](../../aspose.slides.dom/) 구현이 문서를 창이나 프레임에서 제거할 때 발생합니다. 최상위 svg 요소에만 적용됩니다. |
| OnAbort | 11 | 요소가 완전히 로드되기 전에 페이지 로딩이 중단될 때 발생합니다. |
| OnError | 12 | 요소가 제대로 로드되지 않거나 스크립트 실행 중 오류가 발생할 때 발생합니다. |
| OnResize | 13 | 문서 뷰가 크기 조정될 때 발생합니다. 최상위 svg 요소에만 적용됩니다. |
| OnScroll | 14 | 문서 뷰가 X축, Y축 또는 두 축을 따라 이동될 때 발생합니다. 최상위 svg 요소에만 적용됩니다. |
| OnZoom | 15 | 문서 뷰의 줌 레벨이 변경될 때 발생합니다. 최상위 svg 요소에만 적용됩니다. |
| OnBegin | 16 | 애니메이션 요소가 시작될 때 발생합니다. |
| OnEnd | 17 | 애니메이션 요소가 종료될 때 발생합니다. |
| OnRepeat | 18 | 애니메이션 요소가 반복될 때 발생합니다. |

## 관련 항목

* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)
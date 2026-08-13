---
title: get_PathTypes()
second_title: Aspose.Slides for C++ API 참조
description: 요소의 경로에 있는 각 점의 유형을 지정하는 바이트 값 배열을 반환합니다.
type: docs
weight: 27
url: /ko/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() method

요소의 경로에 있는 각 점의 유형을 지정하는 바이트 값 배열을 반환합니다.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## 비고

**0** 은(는) 해당 점이 도형의 시작점임을 나타냅니다.

**1** 은(는) 해당 점이 선의 두 끝점 중 하나임을 나타냅니다.

**3** 은(는) 해당 점이 3차 베지어 스플라인의 끝점 혹은 제어점임을 나타냅니다.

**7** 은(는) 점 유형을 나타내는 세 개의 낮은 순서 비트를 제외한 모든 비트를 마스크합니다.

**16** 은(는) 해당 구간이 점선임을 지정합니다.

**32** 은(는) 해당 점이 마커임을 지정합니다.

**128** 은(는) 해당 점이 닫힌 하위 경로(도형)의 마지막 점임을 지정합니다.

**129** 은(는) 선 구간의 끝점이면서 닫힌 하위 경로의 마지막 점인 데이터 점임을 나타냅니다.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ShapeElement](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
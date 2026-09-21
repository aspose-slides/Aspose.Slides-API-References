---
title: overlap property
second_title: Aspose.Slides for Python via .NET API 참조
description:
type: docs
url: /ko/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## overlap 속성
2-D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100%까지) 로 지정합니다.  
이 속성은 이 시리즈에만 해당되는 것이 아니라 상위 시리즈 그룹의 모든 시리즈에 적용됩니다.  
이는 상위 시리즈 그룹의 해당 속성을 투영한 것이므로 이 속성은 읽기 전용입니다.  
값을 변경하려면 ParentSeriesGroup.Overlap 읽기/쓰기 속성을 사용하십시오.  
읽기 전용 **int**.

### Remarks
Overlap는 막대와 열 사이의 겹침 정도 또는 간격을 너비의 백분율로 지정합니다:
- -100%: 최대 간격 (막대가 완전히 분리됩니다).
- 0%: 막대가 겹치거나 간격 없이 나란히 배치됩니다.
- 100%: 최대 겹침 (막대가 서로 완전히 겹칩니다).
이는 속성 ParentSeriesGroup.Overlap을 투영한 것입니다.

### Definition:
```python
@property
def overlap(self):
    ...
```

### See Also
* 클래스 [`IChartSeries`](/slides/python-net/ko/aspose.slides.charts/ichartseries)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)
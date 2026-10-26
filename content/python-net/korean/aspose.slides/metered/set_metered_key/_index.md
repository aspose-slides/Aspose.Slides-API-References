---
title: set_metered_key method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
계량된 공개 키와 개인 키를 설정합니다.
계량 라이선스를 구매한 경우, 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다.
하지만 소비 데이터 업로드에 계속 실패하고 24시간을 초과하면 라이선스가 평가 상태로 설정됩니다,
이러한 상황을 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 이 API를 다시 호출해야 합니다.

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| public_key | **str** | 공개 키 |
| private_key | **str** | 개인 키 |

### 참고
* 클래스 [`Metered`](/slides/python-net/ko/aspose.slides/metered)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)
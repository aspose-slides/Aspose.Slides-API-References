---
title: set_embedded_data method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/oleobjectframe/set_embedded_data/
weight: 60
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
OLE 삽입 데이터에 대한 정보를 설정합니다.

이 메서드는 새 데이터를 반영하도록 객체의 속성을 변경하고 IsObjectLink 플래그를 false로 설정하여 OLE 객체가 삽입되었음을 나타냅니다.

```python
def set_embedded_data(self, embedded_data):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo) | 삽입 데이터 [`IOleEmbeddedDataInfo`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo) |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | embeddedData 매개변수가 None인 경우. |

### 참고
* 클래스 [`IOleEmbeddedDataInfo`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo)
* 클래스 [`OleObjectFrame`](/slides/python-net/ko/aspose.slides/oleobjectframe)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)
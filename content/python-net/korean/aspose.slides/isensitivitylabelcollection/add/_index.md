---
title: add method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
컬렉션에 SensitivityLabel을 추가합니다.

### 반환값

SensitivityLabel이 추가된 인덱스입니다.



```python
def add(self, label):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/ko/aspose.slides/isensitivitylabel) | 컬렉션 끝에 추가될 SensitivityLabel 객체. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 동일한 Id를 가진 sensitivity label이 이미 추가된 경우 발생합니다. |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/ko/aspose.slides/sensitivitylabelassignmenttype) |  |



### 참고
* 클래스 [`ISensitivityLabel`](/slides/python-net/ko/aspose.slides/isensitivitylabel)
* 클래스 [`ISensitivityLabelCollection`](/slides/python-net/ko/aspose.slides/isensitivitylabelcollection)
* 열거형 [`SensitivityLabelAssignmentType`](/slides/python-net/ko/aspose.slides/sensitivitylabelassignmenttype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)
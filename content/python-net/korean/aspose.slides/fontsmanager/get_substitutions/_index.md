---
title: get_substitutions method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/fontsmanager/get_substitutions/
weight: 60
---
## get_substitutions(self) {#}
프레젠테이션 렌더링 시 교체될 글꼴에 대한 정보를 가져옵니다.

### 반환값

모든 글꼴 대체의 컬렉션 [`FontSubstitutionInfo`](/slides/python-net/ko/aspose.slides/fontsubstitutioninfo).

```python
def get_substitutions(self):
    ...
```

## get_substitutions(self, slides) {#listint}
지정된 슬라이드 렌더링 중 교체될 글꼴에 대한 정보를 가져옵니다.

### 반환값

지정된 슬라이드에 대한 모든 글꼴 대체의 컬렉션 ([`FontSubstitutionInfo`](/slides/python-net/ko/aspose.slides/fontsubstitutioninfo)) 입니다.

```python
def get_substitutions(self, slides):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| slides | **List[int]** | 1부터 시작하는 슬라이드 인덱스 배열로, 해당 슬라이드의 글꼴 대체 정보를 검색합니다. |

### 참고
* 클래스 [`FontsManager`](/slides/python-net/ko/aspose.slides/fontsmanager)
* 클래스 [`FontSubstitutionInfo`](/slides/python-net/ko/aspose.slides/fontsubstitutioninfo)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)
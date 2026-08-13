---
title: IndexOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 지정된 도형이 처음 나타나는 위치의 0부터 시작하는 인덱스를 반환합니다.
type: docs
weight: 313
url: /ko/aspose.slides/shapecollection/indexof/
---
## ShapeCollection::IndexOf(System::SharedPtr\<IShape\>) 메서드

컬렉션에서 지정된 도형이 처음 나타나는 위치의 0부터 시작하는 인덱스를 반환합니다.

```cpp
int32_t Aspose::Slides::ShapeCollection::IndexOf(System::SharedPtr<IShape> shape) override
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 컬렉션에서 찾을 도형입니다. |

### 반환 값

찾은 경우, shape 컬렉션에서 shape가 처음 나타나는 위치의 0부터 시작하는 인덱스; 찾지 못한 경우 \\u20131을 반환합니다.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../../ishape/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
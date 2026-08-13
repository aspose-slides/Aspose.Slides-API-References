---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새로운 빈 그룹 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 그룹의 프레임은 추가된 모든 도형에 맞게 자동으로 조정됩니다.
type: docs
weight: 352
url: /ko/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() 메서드


새로운 빈 그룹 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 그룹의 프레임은 추가된 모든 도형에 맞게 자동으로 조정됩니다.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```


### 반환값

새로 만든 [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) 메서드


새로운 그룹 도형을 생성하고 지정된 SVG 이미지를 개별 도형으로 변환한 뒤, 결과 그룹을 도형 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/)에 포함된 벡터 콘텐츠를 도형으로 변환합니다. |
| x | **float** | 그룹의 프레임 x 좌표(포인트). |
| y | **float** | 그룹의 프레임 y 좌표(포인트). |
| width | **float** | 그룹의 프레임 너비(포인트). |
| height | **float** | 그룹의 프레임 높이(포인트). |

### 반환값

새로 만든 [IGroupShape](../../igroupshape/).

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IGroupShape](../../igroupshape/)
* 클래스 [IShapeCollection](../)
* 클래스 [ISvgImage](../../isvgimage/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
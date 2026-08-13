---
title: GetImage()
second_title: Aspose.Slides C++용 API 참조
description: "모양 썸네일을 반환합니다. ShapeThumbnailBounds::Shape 모양 썸네일 경계 유형은 기본적으로 사용됩니다."
type: docs
weight: 547
url: /ko/aspose.slides/ishape/getimage/
---
## IShape::GetImage() 메서드


모양 썸네일을 반환합니다. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type은 기본적으로 사용됩니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### 반환 값

[Shape](../../shape/) thumbnail.

## IShape::GetImage(ShapeThumbnailBounds, float, float) 메서드


모양 썸네일을 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) thumbnail bounds type. |
| scaleX | **float** | X 스케일 |
| scaleY | **float** | Y 스케일 |

### 반환 값

[Shape](../../shape/) thumbnail 또는 null이며, [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/)가 사용되고 모양에 표시 요소가 없을 경우입니다.

## 참고

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IImage](../../iimage/)
* 클래스 [IShape](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
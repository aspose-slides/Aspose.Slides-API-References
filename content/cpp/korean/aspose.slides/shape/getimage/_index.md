---
title: GetImage()
second_title: C++용 Aspose.Slides API 레퍼런스
description: "shape 썸네일을 반환합니다. ShapeThumbnailBounds::Shape shape 썸네일 경계 유형이 기본값으로 사용됩니다."
type: docs
weight: 651
url: /ko/aspose.slides/shape/getimage/
---
## Shape::GetImage() 메서드

shape 썸네일을 반환합니다. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape 썸네일 경계 유형이 기본값으로 사용됩니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### 반환 값

[Shape](../) 썸네일.

## Shape::GetImage(ShapeThumbnailBounds, float, float) 메서드

shape 썸네일을 반환합니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) 썸네일 경계 유형. |
| scaleX | **float** | X 스케일 |
| scaleY | **float** | Y 스케일 |

### 반환 값

[Shape](../) 썸네일 또는 null은 [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/)가 사용되고 shape에 표시 요소가 없을 경우입니다.

## 참조

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
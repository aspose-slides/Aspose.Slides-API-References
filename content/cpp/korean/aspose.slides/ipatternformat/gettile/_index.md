---
title: GetTile()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 색상으로 패턴 채우기를 위한 타일 이미지를 생성합니다.
type: docs
weight: 53
url: /ko/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) 메서드

패턴 채우기를 위한 타일 이미지를 지정된 색상으로 생성합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | 패턴에 대한 배경 [System::Drawing::Color](../../../system.drawing/color/). |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | 패턴에 대한 전경 [System::Drawing::Color](../../../system.drawing/color/). |

### 반환값

타일 [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) 메서드

패턴 채우기를 위한 타일 이미지를 생성합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | ShapeEx의 StyleEx 객체에 정의된 기본 [System::Drawing::Color](../../../system.drawing/color/). Fill의 색상은 이것에 의존할 수 있습니다. |

### 반환값

타일 [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IImage](../../iimage/)
* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [IPatternFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
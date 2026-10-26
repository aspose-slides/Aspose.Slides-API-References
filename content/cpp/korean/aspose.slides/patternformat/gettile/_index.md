---
title: GetTile()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 색상으로 패턴 채우기를 위한 타일 이미지를 생성합니다.
type: docs
weight: 53
url: /ko/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) 메서드

지정된 색상으로 패턴 채우기를 위한 타일 이미지를 생성합니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | 패턴의 배경 [System::Drawing::Color](../../../system.drawing/color/) |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | 패턴의 전경 [System::Drawing::Color](../../../system.drawing/color/) |

### 반환값

Tile [IImage](../../iimage/).

## PatternFormat::GetTile(System::Drawing::Color) 메서드

패턴 채우기를 위한 타일 이미지를 생성합니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | 기본 [System::Drawing::Color](../../../system.drawing/color/) |

### 반환값

Tile [IImage](../../iimage/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IImage](../../iimage/)
* 클래스 [Color](../../../system.drawing/color/)
* 클래스 [PatternFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
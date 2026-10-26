---
title: GetHeight()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 글꼴의 줄 간격을 지정된 Graphics 객체의 현재 단위로 반환합니다.
type: docs
weight: 14
url: /ko/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) 메서드

현재 객체가 나타내는 글꼴의 줄 간격을, 지정된 [Graphics](../../graphics/) 객체의 현재 단위로 반환합니다.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 측정 단위를 지정하는 [Graphics](../../graphics/) 객체 |

## Font::GetHeight(float) 메서드

지정된 수직 해상도를 가진 디스플레이 장치에 그릴 때 현재 객체가 나타내는 글꼴의 높이를 반환합니다.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dpi | **float** | 디스플레이 장치의 수직 해상도 |

### 반환 값

픽셀 단위의 글꼴 높이

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Graphics](../../graphics/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
---
title: DrawString()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 글꼴과 브러시를 사용하여 지정된 위치에 지정된 문자열을 그립니다.
type: docs
weight: 365
url: /ko/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method

지정된 글꼴과 브러시를 사용하여 지정된 위치에 지정된 문자열을 그립니다.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 그릴 문자열 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 사용할 글꼴 |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 그리기에 사용할 [Brush](../../brush/) 객체 |
| topLeft | [PointF](../../pointf/) | 그려진 문자열의 왼쪽 위 모서리 위치를 지정합니다. |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 문자열의 형식을 지정합니다. |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method

지정된 글꼴과 브러시를 사용하여 지정된 사각형 안에 지정된 문자열을 그립니다.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 그릴 문자열 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 사용할 글꼴 |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 그리기에 사용할 [Brush](../../brush/) 객체 |
| layoutRectangle | [RectangleF](../../rectanglef/) | 문자열을 그릴 사각형을 지정합니다. |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 문자열의 형식을 지정합니다. |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method

지정된 글꼴과 브러시를 사용하여 지정된 위치에 지정된 문자열을 그립니다.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 그릴 문자열 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 사용할 글꼴 |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 그리기에 사용할 [Brush](../../brush/) 객체 |
| x | **float** | 그려진 문자열의 왼쪽 위 모서리 위치의 X 좌표 |
| y | **float** | 그려진 문자열의 왼쪽 위 모서리 위치의 Y 좌표 |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 문자열의 형식을 지정합니다. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
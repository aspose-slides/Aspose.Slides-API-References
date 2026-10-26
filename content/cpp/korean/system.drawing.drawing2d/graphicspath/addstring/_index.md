---
title: AddString()
second_title: Aspose.Slides for C++ API 참조
description: 현재 객체가 나타내는 경로에 텍스트 문자열을 추가합니다.
type: docs
weight: 170
url: /ko/system.drawing.drawing2d/graphicspath/addstring/
---
## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Point, const SharedPtr\<StringFormat\>\&) 메서드

현재 객체가 나타내는 경로에 텍스트 문자열을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, Point origin, const SharedPtr<StringFormat> &stringFormat)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 추가할 텍스트 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 텍스트를 그리는 데 사용되는 글꼴 패밀리 |
| style | int | 사용할 글꼴 스타일을 지정하는 FontStyle 열거형 값 |
| emSize | **float** | 문자열의 각 문자를 둘러싸는 em 정사각형 상자의 높이 |
| origin | [Point](../../../system.drawing/point/) | 텍스트가 시작되는 위치를 지정합니다 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 문자열의 형식 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, PointF, const SharedPtr\<StringFormat\>\&) 메서드

현재 객체가 나타내는 경로에 텍스트 문자열을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, PointF origin, const SharedPtr<StringFormat> &stringFormat)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 추가할 텍스트 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 텍스트를 그리는 데 사용되는 글꼴 패밀리 |
| style | int | 사용할 글꼴 스타일을 지정하는 FontStyle 열거형 값 |
| emSize | **float** | 문자열의 각 문자를 둘러싸는 em 정사각형 상자의 높이 |
| origin | [PointF](../../../system.drawing/pointf/) | 텍스트가 시작되는 위치를 지정합니다 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 문자열의 형식 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, Rectangle, const SharedPtr\<StringFormat\>\&) 메서드

현재 객체가 나타내는 경로에 텍스트 문자열을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, Rectangle layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 추가할 텍스트 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 텍스트를 그리는 데 사용되는 글꼴 패밀리 |
| style | int | 사용할 글꼴 스타일을 지정하는 FontStyle 열거형 값 |
| emSize | **float** | 문자열의 각 문자를 둘러싸는 em 정사각형 상자의 높이 |
| layoutRect | [Rectangle](../../../system.drawing/rectangle/) | 텍스트를 제한하는 사각형 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 문자열의 형식 |

## GraphicsPath::AddString(const String\&, const SharedPtr\<FontFamily\>\&, int, float, RectangleF, const SharedPtr\<StringFormat\>\&) 메서드

현재 객체가 나타내는 경로에 텍스트 문자열을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddString(const String &text, const SharedPtr<FontFamily> &family, int style, float emSize, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 추가할 텍스트 |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../../system.drawing/fontfamily/)\>\& | 텍스트를 그리는 데 사용되는 글꼴 패밀리 |
| style | int | 사용할 글꼴 스타일을 지정하는 FontStyle 열거형 값 |
| emSize | **float** | 문자열의 각 문자를 둘러싸는 em 정사각형 상자의 높이 |
| layoutRect | [RectangleF](../../../system.drawing/rectanglef/) | 텍스트를 제한하는 사각형 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../../system.drawing/stringformat/)\>\& | 문자열의 형식 |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [FontFamily](../../../system.drawing/fontfamily/)
* 클래스 [Point](../../../system.drawing/point/)
* 클래스 [StringFormat](../../../system.drawing/stringformat/)
* 클래스 [GraphicsPath](../)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [Rectangle](../../../system.drawing/rectangle/)
* 클래스 [RectangleF](../../../system.drawing/rectanglef/)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)
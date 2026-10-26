---
title: MeasureString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 형식으로 지정된 글꼴에 그려질 때 지정된 문자열의 크기를 반환합니다.
type: docs
weight: 521
url: /ko/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method

지정된 형식으로 지정된 글꼴에 그려질 때 지정된 문자열의 크기를 반환합니다.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | 크기를 계산할 문자열 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 문자열을 그리는 데 사용되는 글꼴 |
| origin | [PointF](../../pointf/) const\& | 문자열의 왼쪽 위 모서리 위치를 지정합니다 |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 문자열 형식을 지정합니다 |

### 반환값

현재 Grapphics 객체의 PageUnit 속성으로 지정된 측정 단위로 문자열의 크기를 나타내는 [SizeF](../../sizef/) 객체입니다.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method

지정된 형식으로 지정된 글꼴에 그려질 때 지정된 문자열의 크기를 반환합니다.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | 크기를 계산할 문자열 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 문자열을 그리는 데 사용되는 글꼴 |
| width | int | 문자열의 최대 너비 |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 문자열 형식을 지정합니다 |

### 반환값

현재 Grapphics 객체의 PageUnit 속성으로 지정된 측정 단위로 문자열의 크기를 나타내는 [SizeF](../../sizef/) 객체입니다.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method

구현되지 않음.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method

지정된 형식으로 지정된 글꼴에 그려질 때 지정된 문자열의 크기를 반환합니다.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | 크기를 계산할 문자열 |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | 문자열을 그리는 데 사용되는 글꼴 |
| layoutArea | [SizeF](../../sizef/) const\& | 문자열의 최대 레이아웃 영역 |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | 문자열 형식을 지정합니다 |

### 반환값

현재 Grapphics 객체의 PageUnit 속성으로 지정된 측정 단위로 문자열의 크기를 나타내는 [SizeF](../../sizef/) 객체입니다.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [SizeF](../../sizef/)
* 클래스 [String](../../../system/string/)
* 클래스 [Font](../../font/)
* 클래스 [PointF](../../pointf/)
* 클래스 [StringFormat](../../stringformat/)
* 클래스 [Graphics](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)
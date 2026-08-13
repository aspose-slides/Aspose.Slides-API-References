---
title: Font()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 글꼴 스타일을 사용하여 지정된 기존 글꼴을 나타내는 Font 클래스를 새 인스턴스로 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor

지정된 글꼴 스타일을 사용하여 지정된 기존 글꼴을 나타내는 [Font](../) 클래스를 새 인스턴스로 생성합니다.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | 새 인스턴스를 만들기 위한 기존 글꼴 |
| new_style | [FontStyle](../../fontstyle/) | 새 글꼴에 적용할 글꼴 스타일 |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

새 인스턴스를 [Font](../) 클래스로 생성합니다.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | 새 글꼴의 글꼴 패밀리 |
| em_size | **float** | **unit** 매개변수로 지정된 단위의 새 글꼴의 em 크기 |
| style | [FontStyle](../../fontstyle/) | 새 글꼴의 스타일 |
| unit | [GraphicsUnit](../../graphicsunit/) | 새 글꼴의 측정 단위 |
| gdi_charset | **uint8_t** | 새 글꼴에 사용할 GDI 문자 집합 |
| gdi_vertical_font | **bool** | GDI 세로 글꼴에서 파생된 경우 true |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor

새 인스턴스를 [Font](../) 클래스로 생성합니다.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | 새 글꼴의 글꼴 패밀리 |
| em_size | **float** | **unit** 매개변수로 지정된 단위의 새 글꼴의 em 크기 |
| unit | [GraphicsUnit](../../graphicsunit/) | 새 글꼴의 측정 단위 |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

새 인스턴스를 [Font](../) 클래스로 생성합니다.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | 새 글꼴의 글꼴 패밀리 이름 |
| em_size | **float** | **unit** 매개변수로 지정된 단위의 새 글꼴의 em 크기 |
| style | [FontStyle](../../fontstyle/) | 새 글꼴의 스타일 |
| unit | [GraphicsUnit](../../graphicsunit/) | 새 글꼴의 측정 단위 |
| gdi_charset | **uint8_t** | 새 글꼴에 사용할 GDI 문자 집합 |
| gdi_vertical_font | **bool** | GDI 세로 글꼴에서 파생된 경우 true |

## Font::Font(const String\&, float, GraphicsUnit) constructor

새 인스턴스를 [Font](../) 클래스로 생성합니다.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | 새 글꼴의 글꼴 패밀리 이름 |
| em_size | **float** | **unit** 매개변수로 지정된 단위의 새 글꼴의 em 크기 |
| unit | [GraphicsUnit](../../graphicsunit/) | 새 글꼴의 측정 단위 |

## 참조

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
---
title: FontFamily()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름을 가진 글꼴 패밀리를 나타내는 FontFamily 클래스의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) 생성자

[FontFamily](../) 클래스를 새 인스턴스로 생성하고, 지정된 이름을 가진 글꼴 패밀리를 나타냅니다.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 글꼴 패밀리 이름 |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) 생성자

지정된 이름과 지정된 FontCollection에서 [FontFamily](../)의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 글꼴 패밀리 이름 |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | 이 인스턴스를 포함하는 FontCollection |

## FontFamily::FontFamily(Text::GenericFontFamilies) 생성자

지정된 일반 글꼴 패밀리에서 [FontFamily](../)의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | GenericFontFamilies 값으로 [FontFamily](../)을(를) 생성합니다. |

## 참조

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [FontFamily](../)
* 클래스 [FontCollection](../../../system.drawing.text/fontcollection/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)
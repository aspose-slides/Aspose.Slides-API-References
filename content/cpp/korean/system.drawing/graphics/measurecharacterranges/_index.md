---
title: MeasureCharacterRanges()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열에서 문자 위치를 경계하는 영역들의 배열을 반환합니다.
type: docs
weight: 508
url: /ko/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) 메서드

지정된 문자열에서 문자 위치를 경계하는 영역의 배열을 반환합니다.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | 측정할 문자열 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 문자열을 측정하는 동안 사용되는 폰트 |
| layoutRect | [RectangleF](../../rectanglef/) | 문자열을 측정하는 동안 사용되는 레이아웃 사각형 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | 측정할 문자 범위를 포함하는 문자열 형식 |

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Region](../../region/)
* 클래스 [String](../../../system/string/)
* 클래스 [Font](../../font/)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [StringFormat](../../stringformat/)
* 클래스 [Graphics](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)
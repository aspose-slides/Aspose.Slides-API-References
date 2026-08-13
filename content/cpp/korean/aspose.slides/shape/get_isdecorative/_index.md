---
title: get_IsDecorative()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "'Mark as decorative' 옵션을 읽기/쓰기 bool 형식으로 가져옵니다."
type: docs
weight: 521
url: /ko/aspose.slides/shape/get_isdecorative/
---
## Shape::get_IsDecorative() 메서드

'Mark as decorative' 옵션을 읽기/쓰기 **bool** 형식으로 가져옵니다.

```cpp
bool Aspose::Slides::Shape::get_IsDecorative() override
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 참조

* 클래스 [Shape](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
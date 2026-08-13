---
title: set_IsDecorative()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "'Mark as decorative' 옵션을 설정하고 읽기/쓰기 bool."
type: docs
weight: 534
url: /ko/aspose.slides/shape/set_isdecorative/
---
## Shape::set_IsDecorative(bool) 메서드


‘Mark as decorative’ 옵션을 설정하고 읽기/쓰기 **bool**.

```cpp
void Aspose::Slides::Shape::set_IsDecorative(bool value) override
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 참고

* 클래스 [Shape](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: set_IsDecorative()
second_title: Aspose.Slides for C++ API 참조
description: "'Mark as decorative' 옵션을 읽기/쓰기 bool 로 설정합니다."
type: docs
weight: 417
url: /ko/aspose.slides/ishape/set_isdecorative/
---
## IShape::set_IsDecorative(bool) 메서드


'Mark as decorative' 옵션을 읽기/쓰기 **bool** 로 설정합니다.

```cpp
virtual void Aspose::Slides::IShape::set_IsDecorative(bool value)=0
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 참조

* 클래스 [IShape](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
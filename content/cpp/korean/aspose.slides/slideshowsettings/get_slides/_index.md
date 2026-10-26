---
title: get_Slides()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드 범위
type: docs
weight: 118
url: /ko/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const 메서드


[Slides](../../) 범위

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [SlidesRange](../../slidesrange/)
* 클래스 [SlideShowSettings](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
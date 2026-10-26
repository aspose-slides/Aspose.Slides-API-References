---
title: GetLinesCount()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 단락의 줄 수를 가져옵니다.
type: docs
weight: 118
url: /ko/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() 메서드


단락의 줄 수를 반환합니다.

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```


### 반환값

단락의 줄 수
## 비고


예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```


## 참조

* 클래스 [Paragraph](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
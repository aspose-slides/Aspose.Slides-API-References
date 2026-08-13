---
title: get_ParagraphFormat()
second_title: Aspose.Slides for C++ API 참조
description: 이 단락에 대한 서식 개체를 반환합니다. 읽기 전용 IParagraphFormat.
type: docs
weight: 14
url: /ko/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() 메서드

이 단락에 대한 서식 개체를 반환합니다. 읽기 전용 [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## 비고

서식 개체는 현재 단락에만 정의된 서식 매개변수를 포함하며, 상속된 데이터는 적용되지 않습니다.

상속된 값을 포함한 실효값을 가져오려면 [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/) 메서드를 사용하십시오.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IParagraphFormat](../../iparagraphformat/)
* 클래스 [Paragraph](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
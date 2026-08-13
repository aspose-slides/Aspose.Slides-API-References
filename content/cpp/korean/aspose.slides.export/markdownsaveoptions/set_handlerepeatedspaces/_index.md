---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides C++ API 참조
description: Markdown 내보내기 중 반복되는 일반 공백 문자를 어떻게 처리할지 지정합니다.
type: docs
weight: 248
url: /ko/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) method

Markdown 내보내기 중 반복되는 일반 공백 문자들을 어떻게 처리할지 지정합니다.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Remarks

이 속성은 연속된 공백을 다음 중 어떤 방식으로 처리할지 정의합니다:
* 일반 공백 문자로 보존,
* 일반 공백과 비폭발 공백 엔터티(**&nbsp;**)를 교대로 사용,
* 혹은 첫 번째 이후 모두 **&nbsp;** 로 완전히 교체하여 Markdown 출력에서 시각적 정렬을 유지합니다.

기본값은 [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/)입니다. 

## See Also

* 열거형 [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* 클래스 [MarkdownSaveOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)
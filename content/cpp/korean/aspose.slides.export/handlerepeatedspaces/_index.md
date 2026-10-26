---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for C++ API 참조
description: Markdown 내보내기 시 반복되는 일반 공백 문자를 어떻게 처리할지 지정합니다.
type: docs
weight: 937
url: /ko/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces 열거형

반복되는 일반 공백 문자를 Markdown 내보낼 때 어떻게 처리할지 지정합니다.

```cpp
enum class HandleRepeatedSpaces
```

### Values

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 모든 공백은 일반 공백 문자 그대로 보존됩니다. 변환이 적용되지 않으며, 연속된 여러 공백이 있는 경우 그대로 내보내집니다. |
| AlternateSpacesToNbsp | 1 | 두 개 이상의 연속된 일반 공백 시퀀스를 일반 공백 문자와 Non-breaking space 엔티티(**&nbsp;**)를 번갈아 가며 변환합니다. 첫 번째 공백은 항상 일반 공백으로 보존됩니다. |
| MultipleSpacesToNbsp | 2 | 두 개 이상의 연속된 일반 공백 시퀀스를 첫 번째 공백은 일반 공백 문자로 보존하고, 이후의 모든 공백을 Non-breaking space 엔티티(**&nbsp;**)로 교체하여 변환합니다. |

## 참조

* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)
---
title: WarningType
second_title: Aspose.Slides for C++ API 참조
description: 경고 유형을 나타냅니다.
type: docs
weight: 92
url: /ko/aspose.slides.warnings/warningtype/
---
## WarningType 열거형

경고 유형을 나타냅니다.

```cpp
enum class WarningType
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| SourceFileCorruption | 0 | 소스 문서에서 문제가 감지되어 원본 형식으로 저장될 경우 문서를 열 수 없을 가능성이 매우 높습니다. |
| DataLoss | 1 | 텍스트/차트/이미지 또는 기타 데이터가 로드 후 문서 트리에서, 또는 저장 후 생성된 문서에서 완전히 누락됩니다. |
| MajorFormattingLoss | 2 | 중대한 서식 손실. |
| MinorFormattingLoss | 3 | 경미한 서식 손실. |
| CompatibilityIssue | 4 | 이 알려진 문제는 특정 사용자 에이전트 또는 이전 버전의 사용자 에이전트에서 문서를 열지 못하도록 합니다. |
| UnexpectedContent | 99 | 소스 문서의 일부 콘텐츠를 인식할 수 없으며(예: 지원되지 않음), 이는 문제를 일으키거나 데이터/서식 손실을 초래할 수도 있고 그렇지 않을 수도 있습니다. |

## 참조

* 네임스페이스 [Aspose::Slides::Warnings](../)
* 라이브러리 [Aspose.Slides](../../)
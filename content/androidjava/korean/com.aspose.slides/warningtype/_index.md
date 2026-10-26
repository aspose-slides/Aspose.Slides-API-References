---
title: WarningType
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: 경고 유형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/warningtype/
---
**상속:** 
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

경고 유형을 나타냅니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | 소스 문서에서 문제가 감지되어, 원본 형식으로 저장하면 문서를 열 수 없을 가능성이 매우 높습니다. |
| [DataLoss](#DataLoss) | 텍스트/차트/이미지 또는 기타 데이터가 로드 후 문서 트리에서, 또는 저장 후 생성된 문서에서 완전히 누락됩니다. |
| [MajorFormattingLoss](#MajorFormattingLoss) | 주요 서식 손실. |
| [MinorFormattingLoss](#MinorFormattingLoss) | 경미한 서식 손실. |
| [CompatibilityIssue](#CompatibilityIssue) | 이는 특정 사용자 에이전트 또는 이전 버전의 사용자 에이전트에서 문서 열기를 방해하는 알려진 문제입니다. |
| [UnexpectedContent](#UnexpectedContent) | 소스 문서의 일부 콘텐츠를 인식할 수 없습니다 (예: |
### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

소스 문서에서 문제가 감지되어, 원본 형식으로 저장하면 문서를 열 수 없을 가능성이 매우 높습니다.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

텍스트/차트/이미지 또는 기타 데이터가 로드 후 문서 트리에서, 또는 저장 후 생성된 문서에서 완전히 누락됩니다.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

주요 서식 손실.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

경미한 서식 손실.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

이는 특정 사용자 에이전트 또는 이전 버전의 사용자 에이전트에서 문서 열기를 방해하는 알려진 문제입니다.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

소스 문서의 일부 콘텐츠를 인식할 수 없으며(예: 지원되지 않음), 이는 문제를 일으키거나 데이터/서식 손실을 초래할 수도 있고 그렇지 않을 수도 있습니다.
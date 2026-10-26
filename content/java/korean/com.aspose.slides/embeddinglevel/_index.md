---
title: EmbeddingLevel
second_title: Aspose.Slides for Java API 레퍼런스
description: 폰트를 임베드하기 위한 라이선스 권한을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/embeddinglevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

폰트를 임베드하기 위한 라이선스 권한을 나타냅니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Installable](#Installable) | 이 설정이 적용된 글꼴은 애플리케이션에 의해 원격 시스템에 임베드되고 영구적으로 설치될 수 있음을 나타냅니다. |
| [Restricted](#Restricted) | 이 비트만 설정된 글꼴은 법적 소유자의 사전 허가 없이 수정, 임베드 또는 교환될 수 없습니다. |
| [PreviewPrint](#PreviewPrint) | 이 비트가 설정되면 글꼴을 임베드하고 원격 시스템에 일시적으로 로드할 수 있습니다. |
| [Editable](#Editable) | 이 비트가 설정되면 글꼴을 임베드할 수 있지만 다른 시스템에 일시적으로만 설치해야 합니다. |
| [NoSubsetting](#NoSubsetting) | 이 비트가 설정되면 임베드하기 이전에 글꼴을 서브세팅할 수 없습니다. |
| [BitmapOnly](#BitmapOnly) | 이 비트가 설정되면 글꼴에 포함된 비트맵만 임베드할 수 있습니다. |
### 설치 가능 {#Installable}
```
public static final int Installable
```

이 설정이 적용된 글꼴은 애플리케이션에 의해 원격 시스템에 임베드되고 영구적으로 설치될 수 있음을 나타냅니다. 원격 시스템의 사용자는 해당 글꼴에 대해 원 구매자와 동일한 권리, 의무 및 라이선스를 획득하며, 원 구매자와 동일한 최종 사용자 라이선스 계약, 저작권, 디자인 특허 및/또는 상표의 적용을 받습니다.

### 제한됨 {#Restricted}
```
public static final int Restricted
```

이 비트만 설정된 글꼴은 법적 소유자의 사전 허가 없이 수정, 임베드 또는 교환될 수 없습니다.

### 미리보기/인쇄 {#PreviewPrint}
```
public static final int PreviewPrint
```

이 비트가 설정되면 글꼴을 임베드하고 원격 시스템에 일시적으로 로드할 수 있습니다. 미리보기 및 인쇄 글꼴이 포함된 문서는 "읽기 전용"으로 열어야 하며, 문서에 편집을 적용할 수 없습니다.

### 편집 가능 {#Editable}
```
public static final int Editable
```

이 비트가 설정되면 글꼴을 임베드할 수 있지만 다른 시스템에 일시적으로만 설치해야 합니다. 미리보기 및 인쇄 글꼴과 달리, 편집 가능 글꼴이 포함된 문서는 읽기 및 편집이 가능하며 변경 사항을 저장할 수 있습니다.

### 서브세팅 불가 {#NoSubsetting}
```
public static final int NoSubsetting
```

이 비트가 설정되면 글꼴을 임베드하기 전에 서브세팅할 수 없습니다. 비트 0-3 및 9에 지정된 다른 임베드 제한도 적용됩니다.

### 비트맵 전용 {#BitmapOnly}
```
public static final int BitmapOnly
```

이 비트가 설정되면 글꼴에 포함된 비트맵만 임베드할 수 있습니다. 윤곽선 데이터는 임베드할 수 없습니다. 글꼴에 비트맵이 없으면 해당 글꼴은 임베드할 수 없는 것으로 간주되며 임베드 서비스가 실패합니다.
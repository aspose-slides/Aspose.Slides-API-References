---
title: EmbeddingLevel
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 폰트를 삽입하기 위한 라이선스 권한을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/embeddinglevel/
---
**상속:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

폰트를 삽입하기 위한 라이선스 권한을 나타냅니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Installable](#Installable) | 이 설정이 있는 폰트는 애플리케이션에 의해 원격 시스템에 삽입되고 영구적으로 설치될 수 있음을 나타냅니다. |
| [Restricted](#Restricted) | 이 비트만 설정된 폰트는 먼저 법적 소유자의 허가를 얻지 않고는 어떠한 방식으로도 수정, 삽입 또는 교환해서는 안 됩니다. |
| [PreviewPrint](#PreviewPrint) | 이 비트가 설정되면 폰트를 삽입하고 원격 시스템에 일시적으로 로드할 수 있습니다. |
| [Editable](#Editable) | 이 비트가 설정되면 폰트를 삽입할 수 있지만 다른 시스템에 일시적으로만 설치해야 합니다. |
| [NoSubsetting](#NoSubsetting) | 이 비트가 설정되면 폰트를 삽입하기 전에 서브셋팅할 수 없습니다. |
| [BitmapOnly](#BitmapOnly) | 이 비트가 설정되면 폰트에 포함된 비트맵만 삽입할 수 있습니다. |
### 설치 가능 {#Installable}
```
public static final int Installable
```

이 설정이 있는 폰트는 애플리케이션에 의해 원격 시스템에 삽입되고 영구적으로 설치될 수 있음을 나타냅니다. 원격 시스템 사용자는 해당 폰트에 대해 원본 구매자와 동일한 권리, 의무 및 라이선스를 획득하며, 원본 구매자와 동일한 최종 사용자 라이선스 계약, 저작권, 디자인 특허 및/또는 상표의 적용을 받습니다.

### 제한됨 {#Restricted}
```
public static final int Restricted
```

이 비트만 설정된 폰트는 먼저 법적 소유자의 허가를 얻지 않고는 어떠한 방식으로도 수정, 삽입 또는 교환해서는 안 됩니다.

### 미리보기인쇄 {#PreviewPrint}
```
public static final int PreviewPrint
```

이 비트가 설정되면 폰트를 삽입하고 원격 시스템에 일시적으로 로드할 수 있습니다. Preview & Print 폰트를 포함한 문서는 "읽기 전용"으로 열어야 하며, 문서에 편집을 적용할 수 없습니다.

### 편집 가능 {#Editable}
```
public static final int Editable
```

이 비트가 설정되면 폰트를 삽입할 수 있지만 다른 시스템에 일시적으로만 설치해야 합니다. Preview & Print 폰트와 달리, Editable 폰트를 포함한 문서는 읽기 위해 열 수 있으며 편집이 허용되고 변경 사항을 저장할 수 있습니다.

### 하위 집합 불가 {#NoSubsetting}
```
public static final int NoSubsetting
```

이 비트가 설정되면 폰트를 삽입하기 전에 서브셋팅할 수 없습니다. 비트 0-3 및 9에 지정된 다른 삽입 제한도 적용됩니다.

### 비트맵 전용 {#BitmapOnly}
```
public static final int BitmapOnly
```

이 비트가 설정되면 폰트에 포함된 비트맵만 삽입할 수 있습니다. 윤곽 데이터는 삽입될 수 없습니다. 폰트에 비트맵이 없으면 해당 폰트는 삽입할 수 없는 것으로 간주되며 삽입 서비스가 실패합니다.
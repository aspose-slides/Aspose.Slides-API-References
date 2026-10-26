---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/embeddinglevel/
---
## EmbeddingLevel 열거형

폰트를 임베드하는 라이선스 권한을 나타냅니다.

EmbeddingLevel 형식은 다음 멤버를 노출합니다:

## 필드

| 필드 | 설명 |
| :- | :- |
| INSTALLABLE | 이 설정이 지정된 폰트는 응용 프로그램에 의해 원격 시스템에 임베드되고 영구적으로 설치될 수 있음을 나타냅니다. <br/>            원격 시스템 사용자는 해당 폰트에 대해 원본 구매자와 동일한 권리, 의무 및 라이선스를 획득하며, <br/>            원본 구매자와 동일한 최종 사용자 라이선스 계약, 저작권, 디자인 특허 및/또는 상표의 적용을 받습니다. |
| RESTRICTED | 이 비트만 설정된 폰트는 법적 소유자의 허가를 먼저 얻지 않고는 어떠한 방식으로도 수정, 임베드 또는 교환해서는 안 됩니다. |
| PREVIEW_PRINT | 이 비트가 설정되면 폰트를 임베드할 수 있으며 원격 시스템에 일시적으로 로드됩니다. Preview & <br/>            Print 폰트를 포함하는 문서는 "읽기 전용"으로 열어야 하며 문서에 편집을 적용할 수 없습니다. |
| EDITABLE | 이 비트가 설정되면 폰트를 임베드할 수 있지만 다른 시스템에 일시적으로만 설치해야 합니다. Preview & <br/>            Print 폰트와 달리, Editable 폰트를 포함하는 문서는 읽기 전용으로 열 수 있으며 편집이 허용되고 변경 사항을 저장할 수 있습니다. |
| NO_SUBSETTING | 이 비트가 설정되면 폰트를 임베드하기 전에 서브셋팅할 수 없습니다. 비트 0-3 및 9에 지정된 기타 임베드 제한도 적용됩니다. |
| BITMAP_ONLY | 이 비트가 설정되면 폰트에 포함된 비트맵만 임베드할 수 있습니다. 윤곽 데이터는 임베드될 수 없습니다. 폰트에 비트맵이 전혀 없으면 <br/>            해당 폰트는 임베드할 수 없는 것으로 간주되어 임베드 서비스가 실패합니다. |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)
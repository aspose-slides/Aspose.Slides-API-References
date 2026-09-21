---
title: Zip64Mode enumeration
second_title: Aspose.Slides Python용 .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/zip64mode/
---
## Zip64Mode 열거형

OpenXML 파일에 대해 ZIP64 형식 확장을 언제 사용할지 지정합니다.

Zip64Mode 형식은 다음 멤버를 노출합니다:

## 필드

| 필드 | 설명 |
| :- | :- |
| NEVER | ZIP64 형식 확장을 사용하지 않습니다. |
| IF_NECESSARY | 필요할 경우 ZIP64 형식 확장을 사용합니다. |
| ALWAYS | 항상 ZIP64 형식 확장을 사용합니다. |

### 비고

OpenXML 파일은 파일의 압축 해제 크기, 
            파일의 압축 크기 및 아카이브의 총 크기에 4 GB(2^32 바이트)의 제한이 있는 ZIP-archive이며, 
            아카이브 내 파일 수는 65,535(2^16-1)개로 제한됩니다. 
            ZIP64 형식 확장은 이러한 제한을 2^64까지 늘립니다.

### 참조
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)
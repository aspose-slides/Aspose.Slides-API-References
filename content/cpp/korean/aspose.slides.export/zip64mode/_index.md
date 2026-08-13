---
title: Zip64Mode
second_title: Aspose.Slides for C++ API 레퍼런스
description: OpenXML 파일에 대해 ZIP64 형식 확장을 언제 사용할지 지정합니다.
type: docs
weight: 1119
url: /ko/aspose.slides.export/zip64mode/
---
## Zip64Mode 열거형

Specifies when to use ZIP64 format extensions for OpenXML file.

```cpp
enum class Zip64Mode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Never | 0 | ZIP64 형식 확장을 사용하지 않습니다. |
| IfNecessary | 1 | 필요한 경우 ZIP64 형식 확장을 사용합니다. |
| Always | 2 | 항상 ZIP64 형식 확장을 사용합니다. |

## 비고

OpenXML 파일은 파일의 압축 해제 크기, 파일의 압축 크기 및 아카이브 전체 크기에 대해 4 GB(2^32 바이트) 제한과 아카이브 내 파일 수가 65,535(2^16-1)개로 제한되는 ZIP-archive입니다. ZIP64 형식 확장은 제한을 2^64까지 늘립니다.

## 참조

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)
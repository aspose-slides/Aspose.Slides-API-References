---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides for C++ API 레퍼런스
description: any 및 anyAttribute 요소 교체에 대한 검증 모드에 대한 정보를 제공합니다.
type: docs
weight: 976
url: /ko/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum


**any** 및 **anyAttribute** 요소 교체에 대한 검증 모드에 대한 정보를 제공합니다.

```cpp
enum class XmlSchemaContentProcessing
```

### Values

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 문서 항목이 검증되지 않습니다. |
| Skip | 1 | 문서 항목은 잘 형성된 XML이어야 하며 스키마에 의해 검증되지 않습니다. |
| Lax | 2 | 연관된 스키마가 발견되면 문서 항목이 검증됩니다. 그렇지 않으면 오류가 발생하지 않습니다. |
| Strict | 3 | 스키마 프로세서는 지정된 네임스페이스와 연결된 스키마를 찾아 문서 항목을 검증해야 합니다. |

## 참고

* 네임스페이스 [System::Xml::Schema](../)
* 라이브러리 [Aspose.Slides](../../)
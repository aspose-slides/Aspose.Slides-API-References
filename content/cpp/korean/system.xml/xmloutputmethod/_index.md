---
title: XmlOutputMethod
second_title: Aspose.Slides for C++ API 참조
description: XmlWriter 출력물을 직렬화하는 데 사용되는 방법을 지정합니다.
type: docs
weight: 846
url: /ko/system.xml/xmloutputmethod/
---
## XmlOutputMethod 열거형

[XmlWriter](../xmlwriter/) 출력물을 직렬화하는 데 사용되는 메서드를 지정합니다.

```cpp
enum class XmlOutputMethod
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Xml | 0 | XML 1.0 규칙에 따라 직렬화합니다. |
| Html | 1 | XSLT에서 지정한 HTML 규칙에 따라 직렬화합니다. |
| Text | 2 | 텍스트 블록만 직렬화합니다. |
| AutoDetect | 3 | 런타임에 [XmlOutputMethod::Xml](./)와 [XmlOutputMethod::Html](./) 출력 방법 중에서 선택하기 위해 XSLT 규칙을 사용합니다. |

## 참조

* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)
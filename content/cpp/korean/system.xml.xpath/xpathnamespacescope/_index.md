---
title: XPathNamespaceScope
second_title: Aspose.Slides for C++ API 레퍼런스
description: 네임스페이스 범위를 정의합니다.
type: docs
weight: 144
url: /ko/system.xml.xpath/xpathnamespacescope/
---
## XPathNamespaceScope enum

네임스페이스 범위를 정의합니다.

```cpp
enum class XPathNamespaceScope
```

### 값

| Name | Value | Description |
| --- | --- | --- |
| All | 0 | 현재 노드의 범위에 정의된 모든 네임스페이스를 반환합니다. 여기에는 항상 암시적으로 선언되는 **xmlns:xml** 네임스페이스가 포함됩니다. 반환되는 네임스페이스의 순서는 정의되지 않았습니다. |
| ExcludeXml | 1 | 현재 노드의 범위에 정의된 모든 네임스페이스를 반환하지만 **xmlns:xml** 네임스페이스는 제외합니다. **xmlns:xml** 네임스페이스는 항상 암시적으로 선언됩니다. 반환되는 네임스페이스의 순서는 정의되지 않았습니다. |
| Local | 2 | 현재 노드에서 로컬로 정의된 모든 네임스페이스를 반환합니다. |

## 참조

* 네임스페이스 [System::Xml::XPath](../)
* 라이브러리 [Aspose.Slides](../../)
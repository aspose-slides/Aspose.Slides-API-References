---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열과 DateTime 사이를 변환할 때 시간 값을 어떻게 처리할지 지정합니다.
type: docs
weight: 781
url: /ko/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

문자열과 [DateTime](../../system/datetime/) 사이를 변환할 때 시간 값을 어떻게 처리할지 지정합니다.

```cpp
enum class XmlDateTimeSerializationMode
```

### 값

| Name | Value | Description |
| --- | --- | --- |
| Local | 0 | 현지 시간으로 취급합니다. [DateTime](../../system/datetime/) 개체가 협정 세계시(UTC)를 나타내는 경우 현지 시간으로 변환됩니다. |
| Utc | 1 | UTC로 취급합니다. [DateTime](../../system/datetime/) 개체가 현지 시간을 나타내는 경우 UTC로 변환됩니다. |
| Unspecified | 2 | [DateTime](../../system/datetime/)가 문자열로 변환되는 경우 현지 시간으로 취급합니다. 문자열이 [DateTime](../../system/datetime/)로 변환되는 경우, 시간대가 지정된 경우 현지 시간으로 변환합니다. |
| RoundtripKind | 3 | 변환 시 시간대 정보가 보존되어야 합니다. |

## 참고

* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)
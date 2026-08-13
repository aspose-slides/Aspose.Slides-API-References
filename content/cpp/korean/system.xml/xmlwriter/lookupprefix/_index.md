---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 오버라이드될 경우, 현재 네임스페이스 범위에 정의된 가장 가까운 접두사를 해당 네임스페이스 URI에 대해 반환합니다.
type: docs
weight: 352
url: /ko/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix(String) 메서드


파생 클래스에서 오버라이드될 경우, 현재 네임스페이스 범위에 정의된 가장 가까운 접두사를 네임스페이스 URI에 대해 반환합니다.

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ns | [String](../../../system/string/) | 찾고자 하는 접두사가 있는 네임스페이스 URI입니다. |

### 반환값

일치하는 접두사 또는 현재 범위에서 일치하는 네임스페이스 URI가 없을 경우 **nullptr**.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlWriter](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
---
title: ToString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XmlQualifiedName의 문자열 값을 반환합니다.
type: docs
weight: 79
url: /ko/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const 메서드

[XmlQualifiedName](../)의 문자열 값을 반환합니다.

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### 반환 값

[XmlQualifiedName](../)의 문자열 값을 **namespace:localname** 형식으로 반환합니다. 객체에 네임스페이스가 정의되어 있지 않으면, 이 메서드는 로컬 이름만 반환합니다.

## XmlQualifiedName::ToString(const String\&, const String\&) 메서드

[XmlQualifiedName](../)의 문자열 값을 반환합니다.

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 객체의 이름. |
| ns | const [String](../../../system/string/)\& | 객체의 네임스페이스. |

### 반환 값

[XmlQualifiedName](../)의 문자열 값을 **namespace:localname** 형식으로 반환합니다. 객체에 네임스페이스가 정의되어 있지 않으면, 이 메서드는 로컬 이름만 반환합니다.

## 관련 항목

* 클래스 [String](../../../system/string/)
* 클래스 [XmlQualifiedName](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
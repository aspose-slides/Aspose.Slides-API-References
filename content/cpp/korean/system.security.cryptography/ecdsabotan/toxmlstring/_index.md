---
title: ToXmlString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XML 형식으로 모든 매개변수를 내보냅니다. 구현되지 않음.
type: docs
weight: 157
url: /ko/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) 메서드


XML 형식으로 모든 매개변수를 내보냅니다. 구현되지 않음.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| include_private_parameters | **bool** | private 및 public 매개변수를 모두 내보내려면 True, public 매개변수만 내보내려면 false. |

### 반환 값

XML-인코딩된 매개변수.

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) 메서드


XML 형식으로 모든 매변수를 내보냅니다.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | 결과 XML 문자열의 형식. |

### 반환 값

XML-인코딩된 매개변수.

## 참고

* Enum [ECKeyXmlFormat](../../eckeyxmlformat/)
* Class [String](../../../system/string/)
* Class [ECDsaBotan](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
---
title: HashAlgorithmName
second_title: Aspose.Slides for C++ API 참조
description: "해시 알고리즘 이름을 나타내는 문자열. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 사용하지 마십시오."
type: docs
weight: 755
url: /ko/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/)은 해시 알고리즘 이름을 나타냅니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](../../system/smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오.

```cpp
class HashAlgorithmName
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | OID 값에서 [HashAlgorithmName](./)을(를) 생성합니다. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | [MD5](../md5/)를 나타내는 [HashAlgorithmName](./)를 가져옵니다. |
| [String](../../system/string/) [get_Name](./get_name/)() const | 알고리즘 이름의 문자열 표현을 가져옵니다. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | [SHA1](../sha1/)을(를) 나타내는 [HashAlgorithmName](./)를 가져옵니다. |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | [SHA256](../sha256/)을(를) 나타내는 [HashAlgorithmName](./)를 가져옵니다. |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | [SHA384](../sha384/)을(를) 나타내는 [HashAlgorithmName](./)를 가져옵니다. |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | [SHA512](../sha512/)을(를) 나타내는 [HashAlgorithmName](./)를 가져옵니다. |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | 생성자. |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [HashAlgorithmName](./)\& [operator=](./operator_equal/)(const [HashAlgorithmName](./)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| [String](../../system/string/) [ToString](./tostring/)() const | 알고리즘 이름의 문자열 표현을 가져옵니다. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | OID 값에서 [HashAlgorithmName](./)을(를) 생성하려고 시도합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | [TimeSpan](../../system/timespan/) 구조를 나타내는 [TypeInfo](../../system/typeinfo/) 객체를 반환합니다. |

## 참조

* 네임스페이스 [System::Security::Cryptography](../)
* 라이브러리 [Aspose.Slides](../../)
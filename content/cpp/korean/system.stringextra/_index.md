---
title: "System::StringExtra"
second_title: Aspose.Slides for C++ API 참조
description: 
type: docs
weight: 911
url: /ko/system.stringextra/
---
## 함수

| 함수 | 설명 |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | 문자열 배열을 연결합니다. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | 문자열들을 연결합니다. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | 문자열들을 연결합니다. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | 문자열들을 연결합니다. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 여러 객체를 문자열로 변환하고 결과 문자열을 연결합니다. [SmartPtr](../system/smartptr/) 타입에 대한 특수화. |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 여러 객체를 문자열로 변환하고 결과 문자열을 연결합니다. 산술 타입에 대한 특수화. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | 여러 객체를 문자열로 변환하고 결과 문자열을 연결합니다. 구조체 및 기타 값 타입에 대한 특수화. |
---
title: get_IndentChars()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "들여쓰기 할 때 사용할 문자 문자열을 반환합니다. 이 설정은 XmlWriterSettings::set_Indent 값이 true 로 설정된 경우에 사용됩니다."
type: docs
weight: 131
url: /ko/system.xml/xmlwritersettings/get_indentchars/
---
## XmlWriterSettings::get_IndentChars() 메서드


들여쓰기 할 때 사용할 문자 문자열을 반환합니다. 이 설정은 [XmlWriterSettings::set_Indent](../set_indent/) 값이 **true** 로 설정된 경우에 사용됩니다.

```cpp
String System::Xml::XmlWriterSettings::get_IndentChars()
```


### 반환 값

들여쓰기 할 때 사용할 문자 문자열입니다. 이는 任意의 문자열 값으로 설정할 수 있습니다. 그러나 올바른 XML을 보장하려면 공백 문자, 탭, 캐리지 리턴 또는 라인 피드와 같은 유효한 공백 문자만 지정해야 합니다. 기본값은 공백 두 개입니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlWriterSettings](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
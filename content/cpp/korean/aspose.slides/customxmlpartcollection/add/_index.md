---
title: Add()
second_title: Aspose.Slides C++ API 참조
description: 새 사용자 정의 XML 파트를 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) 메서드

새 사용자 정의 xml 파트를 추가합니다.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | 추가될 새 파트의 xml 문자열. |

### 반환 값

생성된 사용자 정의 xml 파트.

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) 메서드

새 사용자 정의 xml 파트를 추가합니다.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 추가될 새 파트의 xml 데이터. |

### 반환 값

생성된 사용자 정의 xml 파트.

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) 메서드

새 사용자 정의 xml 파트를 추가합니다.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 추가될 새 파트의 xml 데이터를 포함하는 inputStream. |

### 반환 값

생성된 사용자 정의 xml 파트.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICustomXmlPart](../../icustomxmlpart/)
* 클래스 [String](../../../system/string/)
* 클래스 [CustomXmlPartCollection](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
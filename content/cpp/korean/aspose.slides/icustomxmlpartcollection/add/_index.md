---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새로운 커스텀 XML 파트를 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) 메서드

새로운 커스텀 XML 파트를 추가합니다.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 추가될 새 파트의 xml 데이터입니다. |

### 반환값

생성된 커스텀 XML 파트.

## ICustomXmlPartCollection::Add(System::String) 메서드

새로운 커스텀 XML 파트를 추가합니다.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | 추가될 새 파트의 xml 문자열입니다. |

### 반환값

생성된 커스텀 XML 파트.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) 메서드

새로운 커스텀 XML 파트를 추가합니다.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 추가될 새 파트의 xml 데이터가 포함된 inputStream입니다. |

### 반환값

생성된 커스텀 XML 파트.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICustomXmlPart](../../icustomxmlpart/)
* 클래스 [ICustomXmlPartCollection](../)
* 클래스 [String](../../../system/string/)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)
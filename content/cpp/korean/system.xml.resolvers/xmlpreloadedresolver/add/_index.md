---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 바이트 배열을 XmlPreloadedResolver 저장소에 추가하고 URI에 매핑합니다. 동일한 URI에 대한 매핑이 이미 저장소에 존재하는 경우 기존 매핑이 덮어써집니다.
type: docs
weight: 79
url: /ko/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) 메서드

[XmlPreloadedResolver](../) 저장소에 바이트 배열을 추가하고 URI에 매핑합니다. 동일한 URI에 대한 매핑이 이미 저장소에 존재하면 기존 매핑이 덮어써집니다.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | [XmlPreloadedResolver](../) 저장소에 추가되는 데이터의 URI. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 제공된 URI에 해당하는 데이터를 포함하는 바이트 배열. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드

[XmlPreloadedResolver](../) 저장소에 바이트 배열을 추가하고 URI에 매핑합니다. 동일한 URI에 대한 매핑이 이미 저장소에 존재하면 기존 매핑이 덮어써집니다.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | [XmlPreloadedResolver](../) 저장소에 추가되는 데이터의 URI. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 제공된 URI에 해당하는 데이터를 포함하는 바이트 배열. |
| offset | **int32_t** | 데이터가 시작되는 바이트 배열 내 오프셋. |
| count | **int32_t** | 제공된 오프셋부터 읽을 바이트 수. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) 메서드

[XmlPreloadedResolver](../) 저장소에 Stream을 추가하고 URI에 매핑합니다. 동일한 URI에 대한 매핑이 이미 저장소에 존재하면 기존 매핑이 덮어써집니다.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | [XmlPreloadedResolver](../) 저장소에 추가되는 데이터의 URI. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 제공된 URI에 해당하는 데이터를 포함하는 Stream. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) 메서드

[XmlPreloadedResolver](../) 저장소에 사전 로드된 데이터를 포함하는 string을 추가하고 URI에 매핑합니다. 동일한 URI에 대한 매핑이 이미 저장소에 존재하면 기존 매핑이 덮어써집니다.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | [XmlPreloadedResolver](../) 저장소에 추가되는 데이터의 URI. |
| value | const [String](../../../system/string/)\& | 제공된 URI와 일치하는 데이터를 포함하는 [String](../../../system/string/). |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [XmlPreloadedResolver](../)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)
---
title: ReadToFollowing()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 한정 이름을 가진 요소가 발견될 때까지 읽습니다.
type: docs
weight: 898
url: /ko/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) 메서드

지정된 한정 이름을 가진 요소가 발견될 때까지 읽습니다.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 요소의 한정 이름입니다. |

### 반환값

**true** 일 경우 일치하는 요소가 발견됩니다; 그렇지 않으면 **false** 이며 [XmlReader](../) 은 파일 끝 상태에 있습니다.

## XmlReader::ReadToFollowing(String, String) 메서드

지정된 로컬 이름과 네임스페이스 URI를 가진 요소가 발견될 때까지 읽습니다.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 요소의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 요소의 네임스페이스 URI입니다. |

### 반환값

**true** 일 경우 일치하는 요소가 발견됩니다; 그렇지 않으면 **false** 이며 [XmlReader](../) 은 파일 끝 상태에 있습니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)
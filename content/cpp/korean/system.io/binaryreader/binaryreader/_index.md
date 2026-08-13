---
title: BinaryReader()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 스트림에서 UTF-8 인코딩을 사용하여 데이터를 읽는 BinaryReader 클래스를 인스턴스화합니다.
type: docs
weight: 1
url: /ko/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) 생성자

[BinaryReader](../) 클래스를 인스턴스화하여 지정된 스트림에서 UTF-8 인코딩을 사용해 데이터를 읽습니다.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 입력 스트림 |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) 생성자

[BinaryReader](../) 클래스를 인스턴스화하여 지정된 스트림에서 지정된 인코딩을 사용해 데이터를 읽습니다.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 입력 스트림 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 사용할 인코딩 |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) 생성자

[BinaryReader](../) 클래스를 인스턴스화하여 지정된 스트림에서 지정된 인코딩을 사용해 데이터를 읽습니다.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 입력 스트림 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 사용할 인코딩 |
| leaveOpen | **bool** | 현재 객체가 해제된 후 스트림 **input**을 열어 둬야 하는지 (**true**) 또는 닫아야 하는지 (**false**)를 지정합니다 |

## 또한 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../stream/)
* 클래스 [BinaryReader](../)
* 클래스 [Encoding](../../../system.text/encoding/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)
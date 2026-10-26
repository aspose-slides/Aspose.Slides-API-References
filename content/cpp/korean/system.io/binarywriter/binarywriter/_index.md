---
title: BinaryWriter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인코딩을 사용하여 지정된 스트림에 데이터를 쓰는 BinaryWriter 클래스의 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) 생성자

[BinaryWriter](../) 클래스를 인스턴스화하여 지정된 인코딩을 사용해 지정된 스트림에 데이터를 씁니다.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 출력 스트림 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |
| leaveopen | **bool** | 현재 객체가 해제된 후 스트림 **stream**을 열어 둬야 하는지(true) 혹은 닫아야 하는지(false)를 지정합니다 |

## 관련 항목

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
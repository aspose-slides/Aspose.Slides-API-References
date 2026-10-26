---
title: BinaryWriter()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт экземпляр класса BinaryWriter, который записывает данные в указанный поток, используя заданную кодировку.
type: docs
weight: 1
url: /ru/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) constructor

Создаёт экземпляр класса [BinaryWriter](../), который записывает данные в указанный поток, используя заданную кодировку.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Выходной поток |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка, которая будет использоваться |
| leaveopen | **bool** | Указывает, следует ли оставлять поток **stream** открытым (true) после того, как текущий объект будет уничтожен, или нет (false) |

## See Also

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
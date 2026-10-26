---
title: BinaryReader()
second_title: Справочник API Aspose.Slides для C++
description: Создает экземпляр класса BinaryReader, который читает данные из указанного потока, используя кодировку UTF-8.
type: docs
weight: 1
url: /ru/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) конструктор

Создает экземпляр класса [BinaryReader](../), который читает данные из указанного потока, используя кодировку UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Входной поток |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) конструктор

Создает экземпляр класса [BinaryReader](../), который читает данные из указанного потока, используя указанную кодировку.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Входной поток |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Кодировка, которую следует использовать |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) конструктор

Создает экземпляр класса [BinaryReader](../), который читает данные из указанного потока, используя указанную кодировку.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Входной поток |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Кодировка, которую следует использовать |
| leaveOpen | **bool** | Указывает, должен ли поток **input** оставаться открытым (true) после того, как текущий объект будет освобождён, или нет (false) |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BinaryReader](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
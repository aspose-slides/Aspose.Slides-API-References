---
title: PeekChar()
second_title: Справочник API Aspose.Slides для C++
description: Читает один символ из входного потока без изменения курсора чтения потока.
type: docs
weight: 53
url: /ru/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() method


Читает один символ из входного потока без изменения курсора чтения потока.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```


### Возвращаемое значение

Считываемый символ кодируется в кодировке UTF-16; если считанный символ представлен двумя кодовыми точками в кодировке UTF-16, то возвращается только старший суррогат; если символ не был считан, возвращается -1

## См. также

* Класс [BinaryReader](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)
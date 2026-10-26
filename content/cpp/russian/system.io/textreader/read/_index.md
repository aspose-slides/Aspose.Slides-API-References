---
title: Read()
second_title: Справочник API Aspose.Slides для C++
description: Считывает один символ из потока.
type: docs
weight: 40
url: /ru/system.io/textreader/read/
---
## TextReader::Read() метод


Считывает один символ из потока.

```cpp
virtual int System::IO::TextReader::Read()
```


### Возвращаемое значение

Считываемый символ закодирован в UTF-16; если символ представляется двумя кодовыми точками в кодировке UTF-16, возвращается только старший суррогат.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) метод


Считывает указанное количество символов из потока и записывает их в указанный массив символов, начиная с указанной позиции.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Массив символов UTF-16, в который записываются считанные из потока символы |
| index | int | Нулевой индекс в **buffer**, с которого начинается запись |
| count | int | Количество символов, которое следует считать из потока |

### Возвращаемое значение

Количество символов, считанных из потока

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
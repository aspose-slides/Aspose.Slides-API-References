---
title: WrapSTDIOStream()
second_title: Справочник API Aspose.Slides для C++
description: "Функция-обёртка для потоков, совместимых со std::basic_istream."
type: docs
weight: 469
url: /ru/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function

Функция-обёртка для потоков, совместимых со std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | Поток, совместимый со std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Режим обёртывания |

### Возвращаемое значение

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) function

Функция-обёртка для потоков, совместимых со std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | Поток, совместимый со std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Режим обёртывания |

### Возвращаемое значение

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) wrapper

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) function

Функция-обёртка для потоков, совместимых со std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | Поток, совместимый со std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Режим обёртывания |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Позиция, которая будет предпочтительной для чтения и записи, если они различаются |

### Возвращаемое значение

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) wrapper

## См. также

* Перечисление [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Перечисление [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Типовое определение [SharedPtr](../../system/sharedptr/)
* Класс [Stream](../stream/)
* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)
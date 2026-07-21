---
title: BasicSTDIOStreamWrapper()
second_title: Aspose.Slides для C++ справки API
description: Создаёт новый экземпляр BasicSTDIOStreamWrapper.
type: docs
weight: 14
url: /ru/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) конструктор


Создаёт новый экземпляр [BasicSTDIOStreamWrapper](../).

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | Ссылка на поток |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Режим обёртывания |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | Позиция, которая будет предпочтительной в качестве позиции чтения и записи, если они различаются |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) конструктор


Конструктор копирования. Удалён.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## См. также

* Перечисление [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Перечисление [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* Типовое определение [char_type](../../stdiostreamwrapperbase/char_type/)
* Типовое определение [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Класс [BasicSTDIOStreamWrapper](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)
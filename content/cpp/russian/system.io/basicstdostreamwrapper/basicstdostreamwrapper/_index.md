---
title: BasicSTDOStreamWrapper()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый экземпляр BasicSTDOStreamWrapper.
type: docs
weight: 14
url: /ru/system.io/basicstdostreamwrapper/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) constructor


Создаёт новый экземпляр [BasicSTDOStreamWrapper](../).

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(std::basic_ostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | std::basic_ostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | Ссылка на поток |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Режим обёртывания |

## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper\&) constructor


Конструктор копирования. Удалён.

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper &)=delete
```

## См. также

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
---
title: BasicSTDIStreamWrapper()
second_title: Aspose.Slides для C++: справочник API
description: Создаёт новый экземпляр BasicSTDIStreamWrapper.
type: docs
weight: 14
url: /ru/system.io/basicstdistreamwrapper/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(std::basic_istream<char_type, traits_type>&, STDIOStreamWrappingMode) конструктор

Создает новый экземпляр [BasicSTDIStreamWrapper](../).

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(std::basic_istream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | std::basic_istream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | Ссылка на поток |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Режим обертывания |

## BasicSTDIStreamWrapper::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper&) конструктор

Конструктор копирования. Удалён.

```cpp
System::IO::BasicSTDIStreamWrapper<T, typename>::BasicSTDIStreamWrapper(const BasicSTDIStreamWrapper &)=delete
```

## See Also

* Перечисление [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Определение типа [char_type](../../stdiostreamwrapperbase/char_type/)
* Определение типа [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Класс [BasicSTDIStreamWrapper](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)
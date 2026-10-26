---
title: StringFormat()
second_title: Aspose.Slides для C++: справочник API
description: Создает новый экземпляр класса StringFormat.
type: docs
weight: 1
url: /ru/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() конструктор


Создает новый экземпляр класса [StringFormat](../).

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) конструктор


Создает новый экземпляр класса [StringFormat](../) с указанными флагами формата и языком.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Битовая комбинация значений перечисления StringFormatFlags, определяющая формат строки, представляемый создаваемым объектом |
| language | **int32_t** | Язык текста |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) конструктор


Конструктор копирования.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Объект [StringFormat](../) для копирования |

## См. также

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [StringFormat](../)
* Пространство имен [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
---
title: StringWriter()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый экземпляр StringWriter, используя указанный StringBuilder и IFormatProvider.
type: docs
weight: 1
url: /ru/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) конструктор


Создает новый экземпляр [StringWriter](../) с использованием указанного StringBuilder и [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Объект StringBuilder, используемый [StringWriter](../) при конструировании |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Объект [IFormatProvider](../../../system/iformatprovider/), используемый создаваемым объектом |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) конструктор


Создает новый экземпляр [StringWriter](../) с использованием указанного StringBuilder и [IFormatProvider](../../../system/iformatprovider/) из текущей культуры.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Объект StringBuilder, используемый [StringWriter](../) при конструировании |

## StringWriter::StringWriter(const IFormatProviderPtr\&) конструктор


Создает новый экземпляр [StringWriter](../) с использованием указанного [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Объект [IFormatProvider](../../../system/iformatprovider/), используемый создаваемым объектом |

## StringWriter::StringWriter() конструктор


Создает новый экземпляр [StringWriter](../) с использованием [IFormatProvider](../../../system/iformatprovider/) из текущей культуры.

```cpp
System::IO::StringWriter::StringWriter()
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Класс [StringBuilder](../../../system.text/stringbuilder/)
* Класс [StringWriter](../)
* Пространство имен [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)
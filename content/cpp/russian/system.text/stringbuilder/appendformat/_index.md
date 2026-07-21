---
title: AppendFormat()
second_title: Aspose.Slides для C++ справочника API
description: Добавляет отформатированную строку в построитель.
type: docs
weight: 131
url: /ru/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String&, const TArgs&...) метод


Добавляет отформатированную строку в построитель.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TArgs | Тип аргументов. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Строка формата. |
| args | const TArgs\&... | Аргументы, вставляемые в позиции строки формата. |

### Возвращаемое значение

Указатель this.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String&, const TArgs&...) метод


Добавляет отформатированную строку в построитель.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TArgs | Тип аргументов. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Поставщик формата; игнорируется. |
| format | const [String](../../../system/string/)\& | Строка формата. |
| args | const TArgs\&... | Аргументы, вставляемые в позиции строки формата. |

### Возвращаемое значение

Указатель this.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [StringBuilder](../)
* Класс [String](../../../system/string/)
* Класс [IFormatProvider](../../../system/iformatprovider/)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)
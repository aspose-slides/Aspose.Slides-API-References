---
title: Parse()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанную строку в эквивалент DateTimeOffset.
type: docs
weight: 703
url: /ru/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) метод


Преобразует указанную строку в эквивалент [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) для преобразования. |

### Возвращаемое значение

[DateTimeOffset](../) который является эквивалентом **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) метод


Преобразует указанную строку в объект [DateTimeOffset](../) с использованием указанного поставщика формата и стиля форматирования.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) для преобразования. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Поставщик формата. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Стили форматирования даты и времени. |

### Возвращаемое значение

[DateTimeOffset](../) который является эквивалентом **input**.

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
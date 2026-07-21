---
title: Format()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает строковое представление значения, представленного текущим объектом, с использованием указанного формата.
type: docs
weight: 1
url: /ru/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) method

Возвращает строковое представление значения, представленного текущим объектом, с использованием указанного формата.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [System::String](../../string/) | Строковый формат |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | Объект для форматирования |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Объект, предоставляющий информацию о форматировании |

### Возвращаемое значение

Строковое представление **arg**, отформатированное в соответствии с форматом, указанным **format** и **formatProvider**

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Object](../../object/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [ICustomFormatter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
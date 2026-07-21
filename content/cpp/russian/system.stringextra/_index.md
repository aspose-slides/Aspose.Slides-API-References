---
title: "System::StringExtra"
second_title: Aspose.Slides для C++ справочник API
description: 
type: docs
weight: 911
url: /ru/system.stringextra/
---
## Функции

| Функция | Описание |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Объединяет массив строк. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Объединяет строки. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Объединяет строки. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Объединяет строки. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Преобразует несколько объектов в строку и объединяет полученные строки. Специализация для [SmartPtr](../system/smartptr/) типов. |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Преобразует несколько объектов в строку и объединяет полученные строки. Специализация для арифметических типов. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Преобразует несколько объектов в строку и объединяет полученные строки. Специализация для структур и других типовых значений. |
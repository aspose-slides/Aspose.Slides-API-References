---
title: Create()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт сравниватель, зависящий от культуры.
type: docs
weight: 79
url: /ru/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) method


Создаёт сравниватель, зависящий от культуры.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Культура, для которой создаётся сравниватель. |
| ignoreCase | **bool** | Определяет, должен ли сравниватель игнорировать регистр. |

### Return Value

Указатель на только что созданный объект сравнивателя.

## See Also

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Класс [CultureInfo](../../../system.globalization/cultureinfo/)
* Класс [StringComparer](../)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)
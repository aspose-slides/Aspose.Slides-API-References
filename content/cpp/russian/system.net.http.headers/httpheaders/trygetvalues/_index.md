---
title: TryGetValues()
second_title: Aspose.Slides для C++ справочника API
description: Пытается получить соответствующие значения по указанному имени.
type: docs
weight: 66
url: /ru/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) method


Пытается получить соответствующие значения по указанному имени.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя заголовка. |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Экземпляр, в который будут записаны соответствующие значения. |

### Возвращаемое значение

True, если значения заголовка найдены по указанному имени, иначе false.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [HttpHeaders](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)
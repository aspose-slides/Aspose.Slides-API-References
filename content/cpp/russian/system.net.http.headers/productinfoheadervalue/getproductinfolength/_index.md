---
title: GetProductInfoLength()
second_title: Aspose.Slides для C++ API Reference
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса ProductInfoHeaderValue.
type: docs
weight: 105
url: /ru/system.net.http.headers/productinfoheadervalue/getproductinfolength/
---
## ProductInfoHeaderValue::GetProductInfoLength(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) метод

Преобразует переданную строку с указанного индекса в экземпляр класса [ProductInfoHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ProductInfoHeaderValue::GetProductInfoLength(String input, int32_t startIndex, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | Экземпляр, в который будет присвоен разобранный объект. |

### Возвращаемое значение

Возвращает длину разобранной подстроки, иначе 0.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [ProductInfoHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)
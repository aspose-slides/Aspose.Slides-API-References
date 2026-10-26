---
title: GetTransferCodingLength()
second_title: Aspose.Slides для C++ справка API
description: Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса TransferCodingHeaderValue.
type: docs
weight: 105
url: /ru/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) метод

Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | [String](../../../system/string/) | Строка для разбора. |
| startIndex | **int32_t** | Начальная позиция для разбора. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Экземпляр, в который будет записан разобранный объект. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | Делегат, используемый для создания экземпляров класса [TransferCodingHeaderValue](../). |

### Возвращаемое значение

Возвращает длину разобранной подстроки, иначе 0.

## См. также

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [TransferCodingHeaderValue](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)
---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт связанный источник токена, который отменяется, когда любой из предоставленных токенов отменяется.
type: docs
weight: 66
url: /ru/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) метод

Создаёт связанный источник токена, который отменяется при отмене любого из предоставленных токенов.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Первый токен отмены для отслеживания. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Второй токен отмены для отслеживания. |

### Возвращаемое значение

Новый источник токена, который будет отменён, когда любой из входных токенов отменяется.

## Примечания

Возвращённый источник будет немедленно отменён, если любой из входных токенов уже отменён.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [CancellationTokenSource](../)
* Класс [CancellationToken](../../cancellationtoken/)
* Пространство имён [System::Threading](../../)
* Library [Aspose.Slides](../../../)
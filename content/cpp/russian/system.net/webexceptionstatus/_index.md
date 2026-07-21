---
title: WebExceptionStatus
second_title: Aspose.Slides для C++ справочник API
description: Перечисляет коды статуса класса WebException.
type: docs
weight: 651
url: /ru/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Перечисляет коды статуса класса WebException.

```cpp
enum class WebExceptionStatus
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Success | 0 | Ошибок не произошло. |
| NameResolutionFailure | 1 | Служба разрешения имён не смогла разрешить имя хоста. |
| ConnectFailure | 2 | Удалённый сервисный узел не может быть достигнут на транспортном уровне. |
| ReceiveFailure | 3 | Полный ответ не получен от удалённого сервера. |
| SendFailure | 4 | Полный запрос не удалось отправить на удалённый сервер. |
| PipelineFailure | 5 | Запрос был конвейерным, и соединение было закрыто до получения ответа. |
| RequestCanceled | 6 | Запрос был отменён или произошла неклассифицируемая ошибка. |
| ProtocolError | 7 | Ответ, полученный от сервера, был полным, но указывал на ошибку уровня протокола. |
| ConnectionClosed | 8 | Соединение было закрыто преждевременно. |
| TrustFailure | 9 | Сертификат сервера не удалось проверить. |
| SecureChannelFailure | 10 | Произошла ошибка при установлении соединения с использованием SSL. |
| ServerProtocolViolation | 11 | Ответ сервера не является корректным HTTP-ответом. |
| KeepAliveFailure | 12 | Соединение для запроса, указывающего заголовок 'Keep-Alive', было закрыто неожиданно. |
| Pending | 13 | Внутренний асинхронный запрос находится в ожидании. |
| Timeout | 14 | Ответ не был получен в течение периода таймаута запроса. |
| ProxyNameResolutionFailure | 15 | Служба разрешения имён не смогла разрешить имя прокси-хоста. |
| UnknownError | 16 | Произошло исключение неизвестного типа. |
| MessageLengthLimitExceeded | 17 | Получено сообщение, превышающее указанный лимит. |
| CacheEntryNotFound | 18 | Указанный элемент кеша не найден. |
| RequestProhibitedByCachePolicy | 19 | Запрос не разрешён политикой кеша. |
| RequestProhibitedByProxy | 20 | Этот запрос не разрешён прокси. |

## См. также

* Пространство имён [System::Net](../)
* Библиотека [Aspose.Slides](../../)
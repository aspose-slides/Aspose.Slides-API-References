---
title: WebExceptionStatus
second_title: Aspose.Slides for C++ – odniesienie API
description: Wylicza kody statusu klasy WebException.
type: docs
weight: 651
url: /pl/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Wylicza kody statusu klasy WebException.

```cpp
enum class WebExceptionStatus
```

### Values

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Success | 0 | Nie wystąpiły żadne błędy. |
| NameResolutionFailure | 1 | Usługa rozwiązywania nazw nie mogła rozwiązać nazwy hosta. |
| ConnectFailure | 2 | Nie udało się skontaktować ze zdalnym punktem usługi na poziomie transportu. |
| ReceiveFailure | 3 | Pełna odpowiedź nie została otrzymana od zdalnego serwera. |
| SendFailure | 4 | Pełne żądanie nie mogło zostać wysłane do zdalnego serwera. |
| PipelineFailure | 5 | Żądanie było żądaniem potokowym, a połączenie zostało zamknięte przed otrzymaniem odpowiedzi. |
| RequestCanceled | 6 | Żądanie zostało anulowane lub wystąpił nieklasyfikowalny błąd. |
| ProtocolError | 7 | Odpowiedź otrzymana z serwera była kompletna, ale wskazywała błąd na poziomie protokołu. |
| ConnectionClosed | 8 | Połączenie zostało przedwcześnie zamknięte. |
| TrustFailure | 9 | Nie udało się zweryfikować certyfikatu serwera. |
| SecureChannelFailure | 10 | Wystąpił błąd podczas nawiązywania połączenia przy użyciu SSL. |
| ServerProtocolViolation | 11 | Odpowiedź serwera nie była prawidłową odpowiedzią HTTP. |
| KeepAliveFailure | 12 | Połączenie dla żądania określającego nagłówek 'Keep-Alive' zostało nieoczekiwanie zamknięte. |
| Pending | 13 | Wewnętrzne żądanie asynchroniczne jest w toku. |
| Timeout | 14 | Nie otrzymano odpowiedzi w okresie oczekiwania (timeout) na żądanie. |
| ProxyNameResolutionFailure | 15 | Usługa rozwiązywania nazw nie mogła rozwiązać nazwy hosta proxy. |
| UnknownError | 16 | Wystąpił wyjątek nieznanego typu. |
| MessageLengthLimitExceeded | 17 | Otrzymano wiadomość, która przekroczyła określony limit. |
| CacheEntryNotFound | 18 | Nie znaleziono określonego wpisu pamięci podręcznej. |
| RequestProhibitedByCachePolicy | 19 | Żądanie nie zostało dopuszczone przez politykę pamięci podręcznej. |
| RequestProhibitedByProxy | 20 | To żądanie nie zostało dopuszczone przez proxy. |

## Zobacz także

* Przestrzeń nazw [System::Net](../)
* Biblioteka [Aspose.Slides](../../)
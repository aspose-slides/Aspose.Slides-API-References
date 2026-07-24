---
title: WebExceptionStatus
second_title: Aspose.Slides für C++ API-Referenz
description: Enumeriert die Statuscodes der WebException-Klasse.
type: docs
weight: 651
url: /de/system.net/webexceptionstatus/
---
## WebExceptionStatus enum

Enumeriert die Statuscodes der WebException-Klasse.

```cpp
enum class WebExceptionStatus
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Success | 0 | Keine Fehler sind aufgetreten. |
| NameResolutionFailure | 1 | Der Namensauflösungsdienst konnte den Hostnamen nicht auflösen. |
| ConnectFailure | 2 | Der Remote-Service-Punkt konnte auf der Transportebene nicht kontaktiert werden. |
| ReceiveFailure | 3 | Eine vollständige Antwort wird vom Remote-Server nicht empfangen. |
| SendFailure | 4 | Eine vollständige Anforderung konnte nicht an den Remote-Server gesendet werden. |
| PipelineFailure | 5 | Die Anfrage war eine pipelined-Anfrage und die Verbindung wurde geschlossen, bevor die Antwort empfangen wurde. |
| RequestCanceled | 6 | Die Anfrage wurde abgebrochen oder ein nicht klassifizierbarer Fehler ist aufgetreten. |
| ProtocolError | 7 | Die vom Server erhaltene Antwort war vollständig, zeigte jedoch einen Protokollfehler an. |
| ConnectionClosed | 8 | Die Verbindung wurde vorzeitig geschlossen. |
| TrustFailure | 9 | Ein Serverzertifikat konnte nicht validiert werden. |
| SecureChannelFailure | 10 | Beim Aufbau einer Verbindung mit SSL ist ein Fehler aufgetreten. |
| ServerProtocolViolation | 11 | Die Serverantwort war keine gültige HTTP-Antwort. |
| KeepAliveFailure | 12 | Die Verbindung für eine Anfrage, die den 'Keep-Alive'-Header spezifiziert, wurde unerwartet geschlossen. |
| Pending | 13 | Eine interne asynchrone Anfrage steht aus. |
| Timeout | 14 | Während des Zeitüberschreitungsintervalls für eine Anfrage wurde keine Antwort empfangen. |
| ProxyNameResolutionFailure | 15 | Der Namensauflösungsdienst konnte den Proxy-Hostnamen nicht auflösen. |
| UnknownError | 16 | Eine Ausnahme unbekannten Typs ist aufgetreten. |
| MessageLengthLimitExceeded | 17 | Eine Nachricht, die das angegebene Limit überschritt, wurde empfangen. |
| CacheEntryNotFound | 18 | Der angegebene Cache-Eintrag wurde nicht gefunden. |
| RequestProhibitedByCachePolicy | 19 | Die Anfrage war durch die Cache-Richtlinie nicht erlaubt. |
| RequestProhibitedByProxy | 20 | Diese Anfrage war durch den Proxy nicht erlaubt. |

## Siehe auch

* Namensraum [System::Net](../)
* Bibliothek [Aspose.Slides](../../)
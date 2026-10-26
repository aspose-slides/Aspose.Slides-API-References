---
title: SocketFlags
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce valori costanti per i messaggi socket.
type: docs
weight: 222
url: /it/system.net.sockets/socketflags/
---
## enum SocketFlags

Fornisce valori costanti per i messaggi socket.

```cpp
enum class SocketFlags
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Non ci sono flag utilizzati per questa chiamata. |
| OutOfBand | 1 | I dati out-of-band sono in fase di elaborazione. |
| Peek | 2 | Visualizza in anteprima un messaggio in arrivo. |
| DontRoute | 4 | Invia un messaggio senza utilizzare le tabelle di routing. |
| Truncated | 256 | Un messaggio è troppo grande per entrare nel buffer specificato. È stato troncato. |
| ControlDataTruncated | 512 | I dati di controllo superano i 64 KB e non entrano nel buffer interno. È stato troncato. |
| Broadcast | 1024 | Un pacchetto broadcast. |
| Multicast | 2048 | Un pacchetto multicast. |
| Partial | 32768 | Un messaggio inviato o ricevuto parzialmente. |

## Vedi anche

* Namespace [System::Net::Sockets](../)
* Libreria [Aspose.Slides](../../)
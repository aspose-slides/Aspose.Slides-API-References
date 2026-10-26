---
title: SocketFlags
second_title: Aspose.Slides pro C++ API Referenci
description: Poskytuje konstantní hodnoty pro socketové zprávy.
type: docs
weight: 222
url: /cs/system.net.sockets/socketflags/
---
## SocketFlags výčet

Poskytuje konstantní hodnoty pro socketových zpráv.

```cpp
enum class SocketFlags
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Pro tento volání nejsou použity žádné příznaky. |
| OutOfBand | 1 | Data mimo pásmo jsou zpracovávána. |
| Peek | 2 | Nahlédnout do příchozí zprávy. |
| DontRoute | 4 | Odeslat zprávu bez použití směrovacích tabulek. |
| Truncated | 256 | Zpráva je příliš velká na to, aby se vešla do zadaného bufferu. Byla zkrácena. |
| ControlDataTruncated | 512 | Řídící data jsou větší než 64 KB a nevejdou do interního bufferu. Byla zkrácena. |
| Broadcast | 1024 | Broadcast paket. |
| Multicast | 2048 | Multicast paket. |
| Partial | 32768 | Zpráva odeslaná nebo přijata částečně. |

## Viz také

* Jmenný prostor [System::Net::Sockets](../)
* Knihovna [Aspose.Slides](../../)
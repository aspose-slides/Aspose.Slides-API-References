---
title: SocketError
second_title: Aspose.Slides for C++ API referencia
description: Felsorolja a socket hiba típusokat.
type: docs
weight: 209
url: /hu/system.net.sockets/socketerror/
---
## SocketError enum

Felsorolja a socket hiba típusokat.

```cpp
enum class SocketError
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Success | 0 | A socket művelet sikeresen befejeződött. |
| SocketError | -1 | Egy nem meghatározott socket hiba történt. |
| Interrupted | 10004 | Egy blokkoló socket hívás megszakadt. |
| AccessDenied | 10013 | A sockethez való hozzáférés megtagadva. |
| Fault | 10014 | Érvénytelen mutatócím került észlelésre. |
| InvalidArgument | 10022 | Érvénytelen argumentum került megadásra. |
| TooManyOpenSockets | 10024 | Túl sok nyitott socket van az alacsony szintű socket szolgáltatónál. |
| WouldBlock | 10035 | Egy művelet nem hajtható végre azonnal egy nem blokkoló socketen. |
| InProgress | 10036 | Egy blokkoló művelet folyamatban van. |
| AlreadyInProgress | 10037 | Egy nem blokkoló socket már futó művelettel rendelkezik. |
| NotSocket | 10038 | Kísérlet egy socket művelet meghívására nem socketen. |
| DestinationAddressRequired | 10039 | Egy szükséges cím hiányzik a socket műveletből. |
| MessageSize | 10040 | A datagram túl hosszú. |
| ProtocolType | 10041 | Ezt a socketet egy protokoll típus nem támogatja. |
| ProtocolOption | 10042 | Ismeretlen, érvénytelen vagy nem támogatott opció vagy szint van használva. |
| ProtocolNotSupported | 10043 | A protokoll nincs megvalósítva vagy nincs konfigurálva. |
| SocketNotSupported | 10044 | Egy címcsalád nem támogatja a megadott socketet. |
| OperationNotSupported | 10045 | Egy protokollcsalád nem támogat egy címcsaládot. |
| ProtocolFamilyNotSupported | 10046 | Egy protokollcsalád nincs megvalósítva vagy nincs konfigurálva. |
| AddressFamilyNotSupported | 10047 | A megadott címcsalád nem támogatott. |
| AddressAlreadyInUse | 10048 | Egy cím csak egyszer használható. |
| AddressNotAvailable | 10049 | A kiválasztott IP-cím ebben a kontextusban nem érvényes. |
| NetworkDown | 10050 | A hálózat nem elérhető. |
| NetworkUnreachable | 10051 | Nem létezik útvonal a távoli géphez. |
| NetworkReset | 10052 | Egy alkalmazás megpróbálta beállítani a “Keep-Alive” értéket egy már időtúllépett kapcsolaton. |
| ConnectionAborted | 10053 | A kapcsolat megszakadt. |
| ConnectionReset | 10054 | A kapcsolatot egy távoli fél visszaállította. |
| NoBufferSpaceAvailable | 10055 | Nincs szabad pufferhely elérhető a socket művelethez. |
| IsConnected | 10056 | A socket már csatlakoztatva van. |
| NotConnected | 10057 | Egy alkalmazás adatküldésre vagy -fogadásra próbált, de a socket nincs csatlakoztatva. |
| Shutdown | 10058 | Az adatküldés vagy -fogadás kérése tiltott, mert a socket már le van zárva. |
| TimedOut | 10060 | A kapcsolódási kísérlet időtúllépést szenvedett, vagy a csatlakozott host nem válaszol. |
| ConnectionRefused | 10061 | A távoli host aktívan visszautasít egy kapcsolatot. |
| HostDown | 10064 | Egy művelet sikertelen, mert a távoli host nem elérhető. |
| HostUnreachable | 10065 | Nem létezik hálózati útvonal a megadott hosthoz. |
| ProcessLimit | 10067 | Túl sok folyamat használja az alacsony szintű socket szolgáltatót. |
| SystemNotReady | 10091 | A hálózati alrendszer nem elérhető. |
| VersionNotSupported | 10092 | Az alacsony szintű socket szolgáltató egy verziója kívül esik a tartományon. |
| NotInitialized | 10093 | Az alacsony szintű socket szolgáltató nincs inicializálva. |
| Disconnecting | 10101 | Egy óvatos leállítás folyamatban van. |
| TypeNotFound | 10109 | A megadott osztály nem található. |
| HostNotFound | 11001 | A megadott host ismeretlen. |
| TryAgain | 11002 | A host neve nem oldható fel. |
| NoRecovery | 11003 | A hiba helyrehozhatatlan vagy a kért adatbázis nem található. |
| NoData | 11004 | A kért név vagy IP-cím nem található a névkiszolgálón. |

## Lásd még

* Névterület [System::Net::Sockets](../)
* Könyvtár [Aspose.Slides](../../)
---
title: SocketError
second_title: Référence API Aspose.Slides pour C++
description: Énumère les types d'erreurs de socket.
type: docs
weight: 209
url: /fr/system.net.sockets/socketerror/
---
## SocketError enum

Énumère les types d'erreurs de socket.

```cpp
enum class SocketError
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Success | 0 | Une opération de socket s'est terminée avec succès. |
| SocketError | -1 | Une erreur de socket non spécifiée s'est produite. |
| Interrupted | 10004 | Un appel de socket bloquant a été annulé. |
| AccessDenied | 10013 | L'accès à une socket est refusé. |
| Fault | 10014 | Une adresse de pointeur invalide a été détectée. |
| InvalidArgument | 10022 | Un argument invalide a été fourni. |
| TooManyOpenSockets | 10024 | Il y a trop de sockets ouvertes dans le fournisseur de sockets sous-jacent. |
| WouldBlock | 10035 | Une opération ne peut pas être immédiatement terminée sur une socket non bloquante. |
| InProgress | 10036 | Une opération bloquante est en cours. |
| AlreadyInProgress | 10037 | Une socket non bloquante a déjà une opération en cours. |
| NotSocket | 10038 | Une tentative d'appeler une opération de socket sur un objet qui n'est pas une socket. |
| DestinationAddressRequired | 10039 | Une adresse requise est omise dans une opération de socket. |
| MessageSize | 10040 | Un datagramme est trop long. |
| ProtocolType | 10041 | Un type de protocole n'est pas pris en charge par cette socket. |
| ProtocolOption | 10042 | Une option ou un niveau inconnu, invalide ou non pris en charge est utilisé. |
| ProtocolNotSupported | 10043 | Un protocole n'est pas implémenté ou n'est pas configuré. |
| SocketNotSupported | 10044 | Une famille d'adresses ne prend pas en charge la socket spécifiée. |
| OperationNotSupported | 10045 | Une famille de protocoles ne prend pas en charge une famille d'adresses. |
| ProtocolFamilyNotSupported | 10046 | Une famille de protocoles n'est pas implémentée ou n'est pas configurée. |
| AddressFamilyNotSupported | 10047 | La famille d'adresses spécifiée n'est pas prise en charge. |
| AddressAlreadyInUse | 10048 | Une adresse ne peut être utilisée qu'une seule fois. |
| AddressNotAvailable | 10049 | L'adresse IP sélectionnée n'est pas valide dans ce contexte. |
| NetworkDown | 10050 | Le réseau n'est pas disponible. |
| NetworkUnreachable | 10051 | Aucune route vers l'hôte distant n'existe. |
| NetworkReset | 10052 | Une application a tenté de définir 'Keep-Alive' sur une connexion qui a déjà expiré. |
| ConnectionAborted | 10053 | Une connexion a été interrompue. |
| ConnectionReset | 10054 | Une connexion a été réinitialisée par un pair distant. |
| NoBufferSpaceAvailable | 10055 | Aucun espace de tampon libre n'est disponible pour une opération de socket. |
| IsConnected | 10056 | Une socket est déjà connectée. |
| NotConnected | 10057 | Une application a essayé d'envoyer ou de recevoir des données, et la socket n'est pas connectée. |
| Shutdown | 10058 | Une demande d'envoi ou de réception de données est interdite parce que la socket a déjà été fermée. |
| TimedOut | 10060 | Une tentative de connexion a expiré, ou un hôte connecté n'a pas répondu. |
| ConnectionRefused | 10061 | Un hôte distant refuse activement une connexion. |
| HostDown | 10064 | Une opération a échoué parce qu'un hôte distant est hors service. |
| HostUnreachable | 10065 | Aucune route réseau vers l'hôte spécifié n'existe. |
| ProcessLimit | 10067 | Trop de processus utilisent le fournisseur de sockets sous-jacent. |
| SystemNotReady | 10091 | Un sous-système réseau est indisponible. |
| VersionNotSupported | 10092 | Une version du fournisseur de sockets sous-jacent est hors plage. |
| NotInitialized | 10093 | Le fournisseur de sockets sous-jacent n'est pas initialisé. |
| Disconnecting | 10101 | Un arrêt gracieux est en cours. |
| TypeNotFound | 10109 | La classe spécifiée n'a pas été trouvée. |
| HostNotFound | 11001 | L'hôte spécifié est inconnu. |
| TryAgain | 11002 | Un nom d'hôte ne peut pas être résolu. |
| NoRecovery | 11003 | Une erreur est irrécouvrable ou la base de données demandée est introuvable. |
| NoData | 11004 | Un nom ou une adresse IP demandée n'a pas été trouvée sur le serveur de noms. |

## Voir aussi

* Espace de noms [System::Net::Sockets](../)
* Bibliothèque [Aspose.Slides](../../)
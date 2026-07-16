---
title: GetHostByAddress()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle instance de la classe IPHostEntry en utilisant la représentation sous forme de chaîne spécifiée d'une adresse IP.
type: docs
weight: 14
url: /fr/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) method

Crée une nouvelle instance de la classe IPHostEntry en utilisant la représentation sous forme de chaîne d'une adresse IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| address | [String](../../../system/string/) | La représentation sous forme de chaîne d'une adresse IP. |

### Valeur de retour

Une nouvelle instance de la classe IPHostEntry.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) method

Crée une nouvelle instance de la classe IPHostEntry en utilisant l'adresse IP spécifiée.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | L'adresse IP. |

### Valeur de retour

Une nouvelle instance de la classe IPHostEntry.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPHostEntry](../../iphostentry/)
* Classe [String](../../../system/string/)
* Classe [Dns](../)
* Classe [IPAddress](../../ipaddress/)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)
---
title: GetHostEntry()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Crée une nouvelle instance de la classe IPHostEntry en utilisant la chaîne spécifiée qui contient un nom d'hôte ou une adresse IP.
type: docs
weight: 79
url: /fr/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) méthode

Crée une nouvelle instance de la classe IPHostEntry en utilisant le string spécifié qui contient un nom d'hôte ou une adresse IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Une string qui contient un nom d'hôte ou une adresse IP. |

### Valeur de retour

Une instance IPHostEntry-class nouvellement créée.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) méthode

Crée une nouvelle instance de la classe IPHostEntry en utilisant l'adresse IP spécifiée.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | L'adresse IP. |

### Valeur de retour

Une instance IPHostEntry-class nouvellement créée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [String](../../../system/string/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
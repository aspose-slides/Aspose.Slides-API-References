---
title: IOControl()
second_title: Référence de l'API C++ d'Aspose.Slides
description: Définit les modes de fonctionnement de bas niveau pour la socket.
type: docs
weight: 703
url: /fr/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) méthode

Définit les modes de fonctionnement de bas niveau pour la socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ioControlCode | **int32_t** | Le code de contrôle de l'opération à exécuter. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets contenant les données d'entrée. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets contenant les données de sortie. |

### Valeur de retour

Le nombre d'octets dans le paramètre **optionOutValue**.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) méthode

Définit les modes de fonctionnement de bas niveau pour la socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | Le code de contrôle de l'opération à exécuter. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets contenant les données d'entrée. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets contenant les données de sortie. |

### Valeur de retour

Le nombre d'octets dans le paramètre **optionOutValue**.

## Voir aussi

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Socket](../)
* Espace de noms [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
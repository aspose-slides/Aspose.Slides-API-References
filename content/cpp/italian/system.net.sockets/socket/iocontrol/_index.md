---
title: IOControl()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta le modalità operative a basso livello per il socket.
type: docs
weight: 703
url: /it/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metodo

Imposta le modalità operative a basso livello per il socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| ioControlCode | **int32_t** | Il codice di controllo dell'operazione da eseguire. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte che contiene i dati di input. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte che contiene i dati di output. |

### Valore di ritorno

Il numero di byte nel parametro **optionOutValue**.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metodo

Imposta le modalità operative a basso livello per il socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | Il codice di controllo dell'operazione da eseguire. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte che contiene i dati di input. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte che contiene i dati di output. |

### Valore di ritorno

Il numero di byte nel parametro **optionOutValue**.

## Vedi anche

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Socket](../)
* Spazio dei nomi [System::Net::Sockets](../../)
* Libreria [Aspose.Slides](../../../)
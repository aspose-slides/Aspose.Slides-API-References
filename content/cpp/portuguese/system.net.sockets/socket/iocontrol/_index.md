---
title: IOControl()
second_title: Referência da API Aspose.Slides for C++
description: Define modos de operação de baixo nível para o soquete.
type: docs
weight: 703
url: /pt/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Define modos de operação de baixo nível para o soquete.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ioControlCode | **int32_t** | O código de controle da operação a ser executada. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes que contém os dados de entrada. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes que contém os dados de saída. |

### Valor de Retorno

O número de bytes no parâmetro **optionOutValue**.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Define modos de operação de baixo nível para o soquete.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | O código de controle da operação a ser executada. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes que contém os dados de entrada. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes que contém os dados de saída. |

### Valor de Retorno

O número de bytes no parâmetro **optionOutValue**.

## Veja Também

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Socket](../)
* Espaço de nomes [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)
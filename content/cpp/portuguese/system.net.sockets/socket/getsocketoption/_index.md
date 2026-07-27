---
title: GetSocketOption()
second_title: Referência da API Aspose.Slides for C++
description: Retorna o valor que corresponde ao nome da opção especificada.
type: docs
weight: 729
url: /pt/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) método


O valor que corresponde ao nome da opção especificado.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | O nível da opção de socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | O nome da opção. |

### Valor de Retorno

O valor que corresponde ao nome da opção especificado.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) método


Obtém o valor que corresponde ao nome da opção especificado.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | O nível da opção de socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | O nome da opção. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O parâmetro de saída onde o valor correspondente será atribuído. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) método


O valor que corresponde ao nome da opção especificado.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | O nível da opção de socket. |
| optionName | [SocketOptionName](../../socketoptionname/) | O nome da opção. |
| optionLength | **int32_t** | O comprimento da opção. |

### Valor de Retorno

O valor que corresponde ao nome da opção especificado.

## Veja Também

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [Socket](../)
* Espaço de nomes [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)
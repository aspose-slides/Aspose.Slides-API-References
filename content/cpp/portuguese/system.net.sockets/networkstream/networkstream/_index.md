---
title: NetworkStream()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância.
type: docs
weight: 170
url: /pt/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) construtor


Constrói uma nova instância.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | O socket usado para enviar e receber dados. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) construtor


Constrói uma nova instância.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | O socket usado para enviar e receber dados. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Especifica o tipo de acesso concedido à instância sobre o socket especificado. |
| ownsSocket | **bool** | Um valor que indica se a instância atual assume a propriedade do socket especificado quando o valor é verdadeiro. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) construtor


Constrói uma nova instância.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | O socket usado para enviar e receber dados. |
| ownsSocket | **bool** | Um valor que indica se a instância atual assume a propriedade do socket especificado quando o valor é verdadeiro. |

## Veja Também

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Socket](../../socket/)
* Classe [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)
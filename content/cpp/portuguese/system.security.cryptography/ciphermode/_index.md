---
title: CipherMode
second_title: Aspose.Slides para C++ Referência da API
description: Modo de cifra em bloco.
type: docs
weight: 885
url: /pt/system.security.cryptography/ciphermode/
---
## CipherMode enum


Modo de cifra em bloco.

```cpp
enum class CipherMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| CBC | 1 | Encadeamento de bloco de cifra que combina o bloco atual com o bloco anterior para melhorar a criptografia. |
| ECB | 2 | Modo de livro-código eletrônico sem influências entre blocos; resulta em criptografia mais fraca. |
| OFB | 3 | Modo de realimentação de saída que processa blocos de entrada grandes em pequenos pedaços. |
| CFB | 4 | Modo de realimentação de cifra que processa blocos de entrada grandes em pequenos pedaços. As regras de processamento diferem das de OFB. |
| CTS | 5 | Modo de roubo de texto cifrado, comporta-se como CBC para todos, exceto os dois últimos blocos do texto. |

## Veja Também

* Namespace [System::Security::Cryptography](../)
* Biblioteca [Aspose.Slides](../../)
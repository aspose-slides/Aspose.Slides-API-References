---
title: GetCookieHeader()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um cabeçalho HTTP que contém cookies associados ao URI especificado.
type: docs
weight: 170
url: /pt/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) método


Retorna um cabeçalho HTTP que contém cookies associados ao URI especificado.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Um URI para o qual o nome do cabeçalho será construído. |

### Valor de Retorno

Um cabeçalho HTTP que contém cookies associados ao URI especificado.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) método


Retorna um cabeçalho HTTP que contém cookies associados ao URI especificado.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Um URI para o qual o nome do cabeçalho será construído. |
| optCookie2 | [String](../../../system/string/)\& | O parâmetro de saída onde um cookie com a versão máxima suportada será atribuído. |

### Valor de Retorno

Um cabeçalho HTTP que contém cookies associados ao URI especificado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Uri](../../../system/uri/)
* Classe [CookieContainer](../)
* Espaço de nomes [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)
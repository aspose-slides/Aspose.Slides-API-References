---
title: GetNameValueLength()
second_title: Referência da API Aspose.Slides para C++
description: Converte uma string fornecida a partir do índice especificado para uma instância da classe NameValueHeaderValue.
type: docs
weight: 118
url: /pt/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) método

Converte uma string fornecida a partir do índice especificado para uma instância da classe [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | [String](../../../system/string/) | Uma string a ser analisada. |
| startIndex | **int32_t** | Uma posição inicial para análise. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Uma instância onde um objeto analisado será atribuído. |

### Valor de Retorno

Retorna o comprimento de uma subsequência analisada, caso contrário 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) método

Converte uma string fornecida a partir do índice especificado para uma instância da classe [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | [String](../../../system/string/) | Uma string a ser analisada. |
| startIndex | **int32_t** | Uma posição inicial para análise. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Uma função usada para criar novas instâncias da classe [NameValueHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Uma instância onde um objeto analisado será atribuído. |

### Valor de Retorno

Retorna o comprimento de uma subsequência analisada, caso contrário 0.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Classe [String](../../../system/string/)
* Classe [NameValueHeaderValue](../)
* Espaço de nomes [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)
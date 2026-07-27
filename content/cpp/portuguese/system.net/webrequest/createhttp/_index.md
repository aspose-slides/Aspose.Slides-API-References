---
title: CreateHttp()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova instância da classe WebRequest usando o URI especificado.
type: docs
weight: 79
url: /pt/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) método

Cria uma nova instância da classe [WebRequest](../) usando o URI especificado.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | O URI que é usado para criar uma nova instância da classe [WebRequest](../). |

### Valor de retorno

Uma nova instância de WebRequest-class.

## Observações



NotSupportedException será lançada quando o URI especificado começar com qualquer esquema, exceto [http://](http://) ou [https://](https://).

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) método


Cria uma nova instância da classe [WebRequest](../) usando o URI especificado.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI que é usado para criar uma nova instância da classe [WebRequest](../). |

### Valor de retorno

Uma nova instância de WebRequest-class.

## Observações



NotSupportedException será lançada quando o URI especificado começar com qualquer esquema, exceto [http://](http://) ou [https://](https://).

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpWebRequest](../../httpwebrequest/)
* Classe [String](../../../system/string/)
* Classe [WebRequest](../)
* Classe [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)
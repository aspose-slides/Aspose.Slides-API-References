---
title: CreateHttp()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova istanza della classe WebRequest utilizzando l'URI specificato.
type: docs
weight: 79
url: /it/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) metodo


Crea una nuova istanza della classe [WebRequest](../) utilizzando l'URI specificato.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | L'URI utilizzato per creare una nuova istanza della classe [WebRequest](../). |

### Valore restituito

Una nuova istanza della classe WebRequest.

## Osservazioni



Verrà generata l'eccezione NotSupportedException quando l'URI specificato inizia con qualsiasi schema diverso da [http://](http://) o [https://](https://). 

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) metodo


Crea una nuova istanza della classe [WebRequest](../) utilizzando l'URI specificato.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI utilizzato per creare una nuova istanza della classe [WebRequest](../). |

### Valore restituito

Una nuova istanza della classe WebRequest.

## Osservazioni



Verrà generata l'eccezione NotSupportedException quando l'URI specificato inizia con qualsiasi schema diverso da [http://](http://) o [https://](https://). 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HttpWebRequest](../../httpwebrequest/)
* Classe [String](../../../system/string/)
* Classe [WebRequest](../)
* Classe [Uri](../../../system/uri/)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)
---
title: Storage
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um armazenamento temporário de dados para .
type: docs
url: /pt/com.aspose.slides/storage/
---
**Herança:**
java.lang.Object
```
public final class Storage
```

Representa um armazenamento temporário de dados para [WebDocument](../../com.aspose.slides/webdocument).
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Storage()](#Storage--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Coloca o valor no armazenamento. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Obtém os dados do armazenamento. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determina se o armazenamento contém um elemento com a chave especificada. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Coloca o valor no armazenamento.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | java.lang.String | Chave para o valor. |
| value | TValue | Valor. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Obtém os dados do armazenamento.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | java.lang.String | Chave do valor. |

**Retorna:**
TValue - Valor dos dados se estiver presente na coleção de dados, null caso contrário.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Determina se o armazenamento contém um elemento com a chave especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| key | java.lang.String | Chave do valor. |

**Retorna:**
boolean - True se o armazenamento contém um elemento com a chave especificada, false caso contrário.
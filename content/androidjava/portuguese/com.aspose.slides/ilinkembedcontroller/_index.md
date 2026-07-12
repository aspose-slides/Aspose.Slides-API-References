---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Interface de retorno de chamada usada para determinar como o objeto deve ser processado durante a gravação.
type: docs
url: /pt/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Interface de retorno de chamada usada para determinar como o objeto deve ser processado durante a gravação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Determina onde o objeto deve ser armazenado. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Retorna uma URL para um objeto externo. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Salva objeto externo. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Determina onde o objeto deve ser armazenado. Este método é chamado uma vez para cada id de objeto. Não há garantia de que não haverá dois objetos com os mesmos dados, semanticName e contentType, mas com ids diferentes.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | int | Id do objeto. Este id é único em toda a operação de gravação. |
| entityData | byte[] | Dados binários do objeto. Este parâmetro pode ser nulo, se os dados binários do objeto ainda não foram gerados. |
| semanticName | java.lang.String | Algum texto curto, descrevendo o significado do objeto. O controlador pode usar isso como parte do nome do objeto externo, mas cabe ao despachante garantir que os nomes sejam únicos e contenham apenas caracteres permitidos. |
| contentType | java.lang.String | Tipo MIME do objeto. |
| recomendedExtension | java.lang.String | Extensão de nome de arquivo recomendada para este tipo MIME. |

**Retorna:**
int - Decisão
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Retorna uma URL para um objeto externo. Este método é sempre chamado se \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) retornou [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) e pode ser chamado se \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) retornou [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) mas a incorporação é impossível. Pode ser chamado várias vezes para o mesmo id de objeto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | int | Id do objeto. Este id é único em toda a operação de gravação. |
| referrer | int | Id do objeto referenciador ou 0, se o objeto for referenciado pelo documento raiz. Pode ser usado para gerar link relativo. |

**Retorna:**
java.lang.String - Url do objeto externo ou null se este objeto deve ser ignorado.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Salva objeto externo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| id | int | Id do objeto. Este id é único em toda a operação de gravação. |
| entityData | byte[] | Dados binários do objeto. Este parâmetro não pode ser nulo. |
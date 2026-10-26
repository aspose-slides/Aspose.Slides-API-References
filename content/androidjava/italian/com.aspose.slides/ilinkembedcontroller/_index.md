---
title: ILinkEmbedController
second_title: Aspose.Slides per Android via Java API Reference
description: Interfaccia di callback usata per determinare come l'oggetto deve essere elaborato durante il salvataggio.
type: docs
url: /it/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Interfaccia di callback usata per determinare come l'oggetto deve essere elaborato durante il salvataggio.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Determina dove l'oggetto deve essere memorizzato. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Restituisce un URL a un oggetto esterno. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Salva l'oggetto esterno. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Determina dove l'oggetto deve essere memorizzato. Questo metodo è chiamato una volta per ogni id di oggetto. Non è garantito che non esistano due oggetti con gli stessi dati, semanticName e contentType ma con id diversi.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | int | Id dell'oggetto. Questo id è univoco per l'intera operazione di salvataggio. |
| entityData | byte[] | Dati binari dell'oggetto. Questo parametro può essere null, se i dati binari dell'oggetto non sono ancora stati generati. |
| semanticName | java.lang.String | Breve testo che descrive il significato dell'oggetto. Il controller può usarlo come parte del nome dell'oggetto esterno, ma spetta al dispatcher garantire che i nomi siano unici e contengano solo i caratteri consentiti. |
| contentType | java.lang.String | Tipo MIME dell'oggetto. |
| recomendedExtension | java.lang.String | Estensione del nome file consigliata per questo tipo MIME. |

**Restituisce:**
int - Decisione
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Restituisce un URL a un oggetto esterno. Questo metodo è sempre chiamato se \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) ha restituito [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) e può essere chiamato se \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) ha restituito [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) ma l'incorporamento è impossibile. Può essere chiamato più volte per lo stesso id di oggetto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | int | Id dell'oggetto. Questo id è univoco per l'intera operazione di salvataggio. |
| referrer | int | Id dell'oggetto di riferimento o 0, se l'oggetto è referenziato dal documento radice. Può essere usato per generare un collegamento relativo. |

**Restituisce:**
java.lang.String - Url dell'oggetto esterno o null se questo oggetto deve essere ignorato.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Salva l'oggetto esterno.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | int | Id dell'oggetto. Questo id è univoco per l'intera operazione di salvataggio. |
| entityData | byte[] | Dati binari dell'oggetto. Questo parametro non può essere null. |
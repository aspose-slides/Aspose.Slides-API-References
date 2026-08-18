---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback-Interface, das bestimmt, wie ein Objekt beim Speichern verarbeitet werden soll.
type: docs
url: /de/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Callback-Interface, das bestimmt, wie ein Objekt beim Speichern verarbeitet werden soll.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Determines where object should be stored. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Returns an URL to an external object. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Saves external object. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Ermittelt, wo das Objekt gespeichert werden soll. Diese Methode wird einmal für jede Objekt-ID aufgerufen. Es ist nicht garantiert, dass es nicht zwei Objekte mit denselben Daten, semanticName und contentType, aber unterschiedlicher ID gibt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | int | Objekt-ID. Diese ID ist für den gesamten Speicher-Vorgang eindeutig. |
| entityData | byte[] | Binärdaten des Objekts. Dieser Parameter kann null sein, wenn die Binärdaten des Objekts noch nicht erzeugt wurden. |
| semanticName | java.lang.String | Ein kurzer Text, der die Bedeutung des Objekts beschreibt. Der Controller kann diesen als Teil des externen Objektnamens verwenden, aber es liegt am Dispatcher sicherzustellen, dass die Namen eindeutig und nur zulässige Zeichen enthalten. |
| contentType | java.lang.String | MIME-Typ des Objekts. |
| recomendedExtension | java.lang.String | Dateinamenerweiterung, die für diesen MIME-Typ empfohlen wird. |

**Rückgabe:**
int - Entscheidung
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Gibt eine URL zu einem externen Objekt zurück. Diese Methode wird immer aufgerufen, wenn \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) zurückgegeben hat und kann aufgerufen werden, wenn \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) zurückgegeben hat, aber Einbetten nicht möglich ist. Kann mehrfach für dieselbe Objekt-ID aufgerufen werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | int | Objekt-ID. Diese ID ist für den gesamten Speicher-Vorgang eindeutig. |
| referrer | int | ID des referenzierenden Objekts oder 0, wenn das Objekt vom Stamm-Dokument referenziert wird. Kann zur Erzeugung eines relativen Links verwendet werden. |

**Rückgabe:**
java.lang.String - URL des externen Objekts oder null, wenn dieses Objekt ignoriert werden soll.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Speichert externes Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | int | Objekt-ID. Diese ID ist für den gesamten Speicher-Vorgang eindeutig. |
| entityData | byte[] | Binärdaten des Objekts. Dieser Parameter darf nicht null sein. |
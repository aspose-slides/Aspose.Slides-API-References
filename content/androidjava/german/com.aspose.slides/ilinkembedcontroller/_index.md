---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
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
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Bestimmt, wo das Objekt gespeichert werden soll. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Gibt eine URL zu einem externen Objekt zurück. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Speichert ein externes Objekt. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Bestimmt, wo das Objekt gespeichert werden soll. Diese Methode wird einmal pro Objekt-ID aufgerufen. Es ist nicht garantiert, dass es nicht zwei Objekte mit denselben Daten, semanticName und contentType, aber unterschiedlicher ID gibt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | int | Objekt-ID. Diese ID ist innerhalb des gesamten Speicher-Vorgangs eindeutig. |
| entityData | byte[] | Objektdaten. Dieser Parameter kann null sein, wenn die Objektdaten noch nicht erzeugt wurden. |
| semanticName | java.lang.String | Ein kurzer Text, der die Bedeutung des Objekts beschreibt. Der Controller kann dies als Teil des externen Objektnamens verwenden, aber es liegt am Dispatcher sicherzustellen, dass die Namen eindeutig sind und nur zulässige Zeichen enthalten. |
| contentType | java.lang.String | MIME-Typ des Objekts. |
| recomendedExtension | java.lang.String | Dateinamenerweiterung, die für diesen MIME-Typ empfohlen wird. |

**Rückgabewert:**
int – Entscheidung
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Gibt eine URL zu einem externen Objekt zurück. Diese Methode wird immer aufgerufen, wenn \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) zurückgegeben hat und kann aufgerufen werden, wenn \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) zurückgegeben hat, aber das Einbetten nicht möglich ist. Kann mehrmals für dieselbe Objekt-ID aufgerufen werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | int | Objekt-ID. Diese ID ist innerhalb des gesamten Speicher-Vorgangs eindeutig. |
| referrer | int | ID des referenzierenden Objekts oder 0, wenn das Objekt vom Root-Dokument referenziert wird. Kann verwendet werden, um einen relativen Link zu erzeugen. |

**Rückgabewert:**
java.lang.String – Url des externen Objekts oder null, wenn dieses Objekt ignoriert werden soll.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Speichert ein externes Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | int | Objekt-ID. Diese ID ist innerhalb des gesamten Speicher-Vorgangs eindeutig. |
| entityData | byte[] | Objektdaten. Dieser Parameter darf nicht null sein. |
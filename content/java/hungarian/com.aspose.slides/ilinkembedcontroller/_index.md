---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /hu/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Callback interfész, amely meghatározza, hogyan kell az objektumot a mentés során feldolgozni.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Determines where object should be stored. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Returns an URL to an external object. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Saves external object. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Meghatározza, hogy hol kell tárolni az objektumot. Ezt a metódust minden egyes objektum-azonosítóhoz egyszer hívják. Nem garantált, hogy nem lesz két objektum ugyanazzal az adatával, semanticName-vel és contentType-tal, de különböző azonosítóval.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | int | Objektum azonosító. Ez az azonosító a mentési művelet során egyedi. |
| entityData | byte[] | Objektum bináris adatai. Ez a paraméter null is lehet, ha az objektum bináris adatai még nem lettek létrehozva. |
| semanticName | java.lang.String | Rövid szöveg, amely leírja az objektum jelentését. A vezérlő ezt felhasználhatja a külső objektumnév részeként, de a diszpatcher feladata biztosítani, hogy a nevek egyediek legyenek, és csak megengedett karaktereket tartalmazzanak. |
| contentType | java.lang.String | Az objektum MIME típusa. |
| recomendedExtension | java.lang.String | Fájlkiterjesztés, amely ajánlott ehhez a MIME típushoz. |

**Visszatérési érték:**
int - Döntés
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Visszaad egy URL-t egy külső objektumhoz. Ez a metódus mindig akkor hívódik, ha \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) értéket adott vissza, és akkor is meghívható, ha \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) értéket adott vissza, de a beágyazás lehetetlen. Többször is meghívható ugyanazzal az objektum azonosítóval.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | int | Objektum azonosító. Ez az azonosító a mentési művelet során egyedi. |
| referrer | int | A hivatkozó objektum azonosítója, vagy 0, ha az objektum a gyökérdokumentum által van hivatkozva. Használható relatív hivatkozás generálásához. |

**Visszatérési érték:**
java.lang.String - Külső objektum URL-je vagy null, ha ezt az objektumot figyelmen kívül kell hagyni.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Külső objektumot ment.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | int | Objektum azonosító. Ez az azonosító a mentési művelet során egyedi. |
| entityData | byte[] | Objektum bináris adatai. Ez a paraméter nem lehet null. |
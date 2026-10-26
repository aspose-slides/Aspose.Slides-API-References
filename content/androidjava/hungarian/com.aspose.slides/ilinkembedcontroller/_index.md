---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /hu/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Visszahívási felület, amely meghatározza, hogyan kell feldolgozni az objektumot a mentés során.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Meghatározza, hogy hol kell tárolni az objektumot. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Visszatér egy URL-lel egy külső objektumra. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Elmenti a külső objektumot. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

Meghatározza, hogy hol kell tárolni az objektumot. Ez a metódus minden egyes objektumazonosítóhoz egyszer kerül meghívásra. Nem garantált, hogy nem lesz két olyan objektum, amelynek ugyanazok az adatai, semanticName és contentType értéke, de különböző azonosítóval rendelkezik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | int | Az objektum azonosítója. Ez az azonosító a mentési művelet során egyedi. |
| entityData | byte[] | Az objektum bináris adatai. Ez a paraméter lehet null, ha az objektum bináris adatai még nem lettek generálva. |
| semanticName | java.lang.String | Rövid szöveg, amely leírja az objektum jelentését. A vezérlő felhasználhatja ezt a külső objektum nevének részeként, de a diszpécser feladata biztosítani, hogy a nevek egyediek legyenek, és csak engedélyezett karaktereket tartalmazzanak. |
| contentType | java.lang.String | Az objektum MIME típusa. |
| recomendedExtension | java.lang.String | A fájlkiterjesztés, amely erre a MIME típusra ajánlott. |

**Visszatér:**
int - Decision
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

Visszatér egy URL-lel egy külső objektumra. Ez a metódus mindig meghívódik, ha \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) értéket ad vissza, és hívható, ha \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) értéket ad vissza, de a beágyazás lehetetlen. Többször is meghívható ugyanarra az objektumazonosítóra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | int | Az objektum azonosítója. Ez az azonosító a mentési művelet során egyedi. |
| referrer | int | Az a hivatkozó objektum azonosítója vagy 0, ha az objektum a gyökérdokumentum által van hivatkozva. Használható relatív hivatkozás generálásához. |

**Visszatér:**
java.lang.String - A külső objektum URL-je, vagy null, ha ezt az objektumot figyelmen kívül kell hagyni.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

Elmenti a külső objektumot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | int | Az objektum azonosítója. Ez az azonosító a mentési művelet során egyedi. |
| entityData | byte[] | Az objektum bináris adatai. Ez a paraméter nem lehet null. |
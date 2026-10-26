---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /cs/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Rozhraní zpětného volání používané k určení, jak má být objekt zpracován během ukládání.
## Metody

| Metoda | Popis |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Určuje, kde by měl být objekt uložen. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Vrací URL k externímu objektu. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Uloží externí objekt. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Určuje, kde by měl být objekt uložen. Tato metoda je volána jednou pro každý identifikátor objektu. Není zaručeno, že nebudou existovat dva objekty se stejnými daty, semanticName a contentType, ale s různými identifikátory.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | int | Identifikátor objektu. Tento identifikátor je v rámci ukládací operace jedinečný. |
| entityData | byte[] | Binární data objektu. Tento parametr může být null, pokud binární data objektu ještě nebyla vygenerována. |
| semanticName | java.lang.String | Krátký text popisující význam objektu. Kontroler jej může použít jako část názvu externího objektu, ale na dispečerovi záleží, aby zajistil jedinečnost názvů a aby obsahovaly pouze povolené znaky. |
| contentType | java.lang.String | MIME typ objektu. |
| recomendedExtension | java.lang.String | Přípona souboru doporučená pro tento MIME typ. |

**Vrací:**
int - Rozhodnutí
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Vrací URL k externímu objektu. Tato metoda je vždy volána, pokud \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) vrátila [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) a může být volána, pokud \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) vrátila [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed), ale vložení není možné. Může být volána vícekrát pro stejný identifikátor objektu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | int | Identifikátor objektu. Tento identifikátor je v rámci ukládací operace jedinečný. |
| referrer | int | Identifikátor odkazujícího objektu nebo 0, pokud je objekt odkazován kořenovým dokumentem. Může být použit k vytvoření relativního odkazu. |

**Vrací:**
java.lang.String - URL externího objektu nebo null, pokud má být tento objekt ignorován.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Uloží externí objekt.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | int | Identifikátor objektu. Tento identifikátor je v rámci ukládací operace jedinečný. |
| entityData | byte[] | Binární data objektu. Tento parametr nesmí být null. |
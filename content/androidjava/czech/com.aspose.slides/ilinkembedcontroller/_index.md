---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Rozhraní zpětného volání používané k určení, jak má být objekt zpracován během ukládání.
type: docs
url: /cs/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Rozhraní zpětného volání používané k určení, jak má být objekt zpracován během ukládání.
## Metody

| Method | Description |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Určuje, kde má být objekt uložen. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Vrací URL externího objektu. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Uloží externí objekt. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Určuje, kde má být objekt uložen. Tato metoda je volána jednou pro každé ID objektu. Není zaručeno, že nebudou dva objekty se stejnými daty, semanticName a contentType, ale s různým ID.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | int | ID objektu. Toto ID je v rámci operace ukládání jedinečné. |
| entityData | byte[] | Binární data objektu. Tento parametr může být null, pokud binární data objektu ještě nebyla vygenerována. |
| semanticName | java.lang.String | Krátký text popisující význam objektu. Řadič může toto použít jako část názvu externího objektu, ale je na dispatcherovi zajistit, aby názvy byly jedinečné a obsahovaly jen povolené znaky. |
| contentType | java.lang.String | MIME typ objektu. |
| recomendedExtension | java.lang.String | Doporučená přípona souboru pro tento MIME typ. |

**Vrací:**  
int - Rozhodnutí
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Vrací URL externího objektu. Tato metoda je vždy volána, pokud #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) vrátila [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) a může být volána, pokud #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) vrátila [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed), ale vložení je nemožné. Může být volána vícekrát pro stejné ID objektu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | int | ID objektu. Toto ID je v rámci operace ukládání jedinečné. |
| referrer | int | ID odkazujícího objektu nebo 0, pokud je objekt odkazován kořenovým dokumentem. Může být použito k vytvoření relativního odkazu. |

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
| id | int | ID objektu. Toto ID je v rámci operace ukládání jedinečné. |
| entityData | byte[] | Binární data objektu. Tento parametr nesmí být null. |
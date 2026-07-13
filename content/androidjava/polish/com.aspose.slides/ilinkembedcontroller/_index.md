---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Interfejs wywołania zwrotnego używany do określenia, jak obiekt powinien być przetwarzany podczas zapisywania.
type: docs
url: /pl/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Interfejs wywołania zwrotnego używany do określenia, jak obiekt powinien być przetwarzany podczas zapisywania.
## Metody

| Metoda | Opis |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Określa, gdzie obiekt powinien być przechowywany. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Zwraca adres URL do zewnętrznego obiektu. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Zapisuje zewnętrzny obiekt. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Określa, gdzie obiekt powinien być przechowywany. Ta metoda jest wywoływana raz dla każdego identyfikatora obiektu. Nie ma gwarancji, że nie wystąpią dwa obiekty o tych samych danych, semanticName i contentType, ale o różnych identyfikatorach.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| id | int | Id obiektu. Ten identyfikator jest unikalny w całej operacji zapisu. |
| entityData | byte[] | Binarnie dane obiektu. Ten parametr może być null, jeśli binarne dane obiektu nie zostały jeszcze wygenerowane. |
| semanticName | java.lang.String | Krótki tekst opisujący znaczenie obiektu. Kontroler może używać tego jako części nazwy zewnętrznego obiektu, ale to od dyspozytora zależy zapewnienie, że nazwy będą unikalne i będą zawierały wyłącznie dozwolone znaki. |
| contentType | java.lang.String | Typ MIME obiektu. |
| recomendedExtension | java.lang.String | Rozszerzenie nazwy pliku zalecane dla tego typu MIME. |

**Zwraca:**
int - Decyzja
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Zwraca adres URL do zewnętrznego obiektu. Ta metoda zawsze jest wywoływana, jeśli \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) zwróciło [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) i może być wywołana, jeśli \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) zwróciło [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed), ale wstawienie jest niemożliwe. Może być wywoływana wielokrotnie dla tego samego identyfikatora obiektu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| id | int | Id obiektu. Ten identyfikator jest unikalny w całej operacji zapisu. |
| referrer | int | Id obiektu odwołującego się lub 0, jeśli obiekt jest odwoływany przez dokument główny. Może być użyty do generowania linku względnego. |

**Zwraca:**
java.lang.String - Url zewnętrznego obiektu lub null, jeśli ten obiekt powinien być zignorowany.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Zapisuje zewnętrzny obiekt.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| id | int | Id obiektu. Ten identyfikator jest unikalny w całej operacji zapisu. |
| entityData | byte[] | Binarnie dane obiektu. Ten parametr nie może być null. |
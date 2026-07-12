---
title: Storage
second_title: Aspose.Slides for Android Java API referenciához
description: Ideiglenes adat tárolót képvisel a .
type: docs
url: /hu/com.aspose.slides/storage/
---
**Öröklés:**
java.lang.Object
```
public final class Storage
```

[WebDocument](../../com.aspose.slides/webdocument) számára ideiglenes adat tárolót képvisel.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Storage()](#Storage--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Az értéket a tárolóba helyezi. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | A tárolóból lekéri az adatot. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Megállapítja, hogy a tároló tartalmaz-e egy elemet a megadott kulccsal. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Az értéket a tárolóba helyezi.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | java.lang.String | Az érték kulcsa. |
| value | TValue | Érték. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


A tárolóból lekéri az adatot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | java.lang.String | A kulcs a tárolóban. |

**Visszatérési érték:**
TValue - Az adat értéke, ha a gyűjteményben megtalálható, egyébként null.

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Megállapítja, hogy a tároló tartalmaz-e egy elemet a megadott kulccsal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | java.lang.String | A kulcs a tárolóban. |

**Visszatérési érték:**
boolean - Igaz, ha a tároló tartalmaz egy elemet a megadott kulccsal, egyébként hamis.
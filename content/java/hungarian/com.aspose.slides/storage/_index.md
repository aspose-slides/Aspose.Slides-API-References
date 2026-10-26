---
title: Storage
second_title: Aspose.Slides Java API referenciája
description: Ideiglenes adattárolót képvisel a .
type: docs
url: /hu/com.aspose.slides/storage/
---
**Öröklés:**
java.lang.Object
```
public final class Storage
```

Ideiglenes adattárolót képvisel a [WebDocument](../../com.aspose.slides/webdocument) számára.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Storage()](#Storage--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Az értéket a tárolóba helyezi. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Lekéri az adatot a tárolóból. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Megállapítja, hogy a tároló tartalmaz-e elemet a megadott kulccsal. |
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

Lekéri az adatot a tárolóból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | java.lang.String | Az érték kulcsa. |

**Visszatérési érték:**
TValue – Az adatérték, ha a gyűjteményben szerepel, egyébként null.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

Megállapítja, hogy a tároló tartalmaz-e elemet a megadott kulccsal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | java.lang.String | Az érték kulcsa. |

**Visszatérési érték:**
boolean – True, ha a tároló tartalmaz olyan elemet, amelynek a kulcsa a megadott, egyébként false.
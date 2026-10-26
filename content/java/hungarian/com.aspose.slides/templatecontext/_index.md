---
title: TemplateContext
second_title: Aspose.Slides Java API Referencia
description: Model objektum interfészt képvisel egy sablonmotor számára.
type: docs
url: /hu/com.aspose.slides/templatecontext/
---
**Öröklés:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Model objektum interfészt képvisel egy sablonmotor számára.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Létrehoz egy gyermek sablonkontextust. |
| [getObject()](#getObject--) | Visszaadja a modell objektumot. |
| [getOutput()](#getOutput--) | Visszaadja a gazda dokumentum kimeneti elemeinek gyűjteményét. |
| [getLocal()](#getLocal--) | Visszaadja az aktuális sablonkontextus helyi tárolóját. |
| [getGlobal()](#getGlobal--) | Visszaadja a gazda dokumentum globális tárolóját. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Létrehoz egy gyermek sablonkontextust.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subModel | TSubModel | Gyermek modell objektum. |

**Visszatérési érték:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Új sablonkontextus a megadott modellel és a szülő kimeneti gyűjteményével és globális tárolójával.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Visszaadja a modell objektumot. Csak olvasható Object.

**Visszatérési érték:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Visszaadja a gazda dokumentum kimeneti elemeinek gyűjteményét. Csak olvasható [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Visszatérési érték:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Visszaadja az aktuális sablonkontextus helyi tárolóját. Csak olvasható [Storage](../../com.aspose.slides/storage).

**Visszatérési érték:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Visszaadja a gazda dokumentum globális tárolóját. Csak olvasható [Storage](../../com.aspose.slides/storage).

**Visszatérési érték:**
[Storage](../../com.aspose.slides/storage)
---
title: TemplateContext
second_title: Aspose.Slides for Android a Java API hivatkozáson keresztül
description: Egy sablonmotor számára modellobjektum interfészt képvisel.
type: docs
url: /hu/com.aspose.slides/templatecontext/
---
**Öröklődés:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Egy sablonmotor számára modellobjektum interfészt képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Gyermek sablonkörnyezetet hoz létre. |
| [getObject()](#getObject--) | Visszaadja a modellobjektumot. |
| [getOutput()](#getOutput--) | Visszaadja a gazda dokumentum kimeneti elemeinek gyűjteményét. |
| [getLocal()](#getLocal--) | Visszaadja az aktuális sablonkörnyezet helyi tárolóját. |
| [getGlobal()](#getGlobal--) | Visszaadja a gazda dokumentum globális tárolóját. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

Gyermek sablonkörnyezetet hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subModel | TSubModel | Gyermek modellobjektum. |

**Visszatérési érték:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Új sablonkörnyezet a megadott modellel, a szülő kimeneti gyűjteményével és globális tárolójával.
### getObject() {#getObject--}
```
public final TObject getObject()
```

Visszaadja a modellobjektumot. Csak olvasható Object.

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

Visszaadja az aktuális sablonkörnyezet helyi tárolóját. Csak olvasható [Storage](../../com.aspose.slides/storage).

**Visszatérési érték:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Visszaadja a gazda dokumentum globális tárolóját. Csak olvasható [Storage](../../com.aspose.slides/storage).

**Visszatérési érték:**
[Storage](../../com.aspose.slides/storage)
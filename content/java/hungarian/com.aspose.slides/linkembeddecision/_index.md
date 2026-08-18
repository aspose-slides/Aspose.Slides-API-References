---
title: LinkEmbedDecision
second_title: Aspose.Slides Java API referencia
description: Meghatározza, hogyan lesz feldolgozva az objektum mentéskor.
type: docs
url: /hu/com.aspose.slides/linkembeddecision/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Meghatározza, hogy az objektum hogyan lesz feldolgozva mentéskor.
## Mezők

| Mező | Leírás |
| --- | --- |
| [Link](#Link) | Az objektum külsőként lesz tárolva, URL-re hivatkozva |
| [Embed](#Embed) | Az objektumot be kell ágyazni egy generált fájlba, ha lehetséges. |
| [Ignore](#Ignore) | Az objektum mellőzve lesz. |
### Hivatkozás {#Link}
```
public static final int Link
```


Az objektum külsőként lesz tárolva, URL-re hivatkozva

### Beágyazás {#Embed}
```
public static final int Embed
```


Az objektumot be kell ágyazni egy generált fájlba, ha lehetséges. Ha a beágyazás lehetetlen, a GetUrl függvényt hívják, és az eredménytől függően az objektum URL-re hivatkozik vagy mellőzve lesz.

### Mellőzés {#Ignore}
```
public static final int Ignore
```


Az objektum mellőzve lesz.
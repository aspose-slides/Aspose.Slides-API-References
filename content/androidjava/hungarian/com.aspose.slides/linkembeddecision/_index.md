---
title: LinkEmbedDecision
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Meghatározza, hogyan lesz az objektum feldolgozva mentéskor.
type: docs
url: /hu/com.aspose.slides/linkembeddecision/
---
**Öröklődés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Meghatározza, hogyan lesz az objektum feldolgozva mentéskor.
## Mezők

| Mező | Leírás |
| --- | --- |
| [Link](#Link) | Az objektum külsőleg lesz tárolva, URL-re hivatkozva |
| [Embed](#Embed) | Az objektumot be kell ágyazni a generált fájlba, ha lehetséges. |
| [Ignore](#Ignore) | Az objektum figyelmen kívül lesz hagyva. |
### Hivatkozás {#Link}
```
public static final int Link
```


Az objektum külsőleg lesz tárolva, URL-re hivatkozva

### Beágyazás {#Embed}
```
public static final int Embed
```


Az objektumot be kell ágyazni a generált fájlba, ha lehetséges. Ha a beágyazás lehetetlen, a GetUrl függvény lesz meghívva, és az eredménytől függően az objektum URL-re hivatkozik vagy figyelmen kívül marad.

### Figyelmen kívül hagyás {#Ignore}
```
public static final int Ignore
```


Az objektum figyelmen kívül lesz hagyva.
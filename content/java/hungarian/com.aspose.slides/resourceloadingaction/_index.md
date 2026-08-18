---
title: ResourceLoadingAction
second_title: Aspose.Slides Java API hivatkozás
description: Meghatározza a külső erőforrás betöltésének módját.
type: docs
url: /hu/com.aspose.slides/resourceloadingaction/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Megadja a külső erőforrás betöltésének módját.
## Mezők

| Mező | Leírás |
| --- | --- |
| [Default](#Default) | Az Aspose.Slides a külső erőforrást a szokásos módon tölti be. |
| [Skip](#Skip) | Az Aspose.Slides kihagyja a külső erőforrás betöltését. |
| [UserProvided](#UserProvided) | Az Aspose.Slides a felhasználó által a [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) metódusban megadott byte tömböt használja képadatokként. |
### Default {#Default}
```
public static final int Default
```


Az Aspose.Slides a külső erőforrást a szokásos módon tölti be.

### Skip {#Skip}
```
public static final int Skip
```


Az Aspose.Slides kihagyja a külső erőforrás betöltését. Csak a adat nélküli hivatkozás lesz tárolva a képhez.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```


Az Aspose.Slides a felhasználó által a [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) metódusban megadott byte tömböt használja képadatokként.
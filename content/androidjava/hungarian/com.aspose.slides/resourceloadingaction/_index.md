---
title: ResourceLoadingAction
second_title: Aspose.Slides for Android Java API hivatkozás
description: Megadja a külső erőforrás betöltésének módját.
type: docs
url: /hu/com.aspose.slides/resourceloadingaction/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Meghatározza a külső erőforrás betöltésének módját.
## Mezők

| Mező | Leírás |
| --- | --- |
| [Default](#Default) | Az Aspose.Slides a szokásos módon tölti be a külső erőforrást. |
| [Skip](#Skip) | Az Aspose.Slides kihagyja a külső erőforrás betöltését. |
| [UserProvided](#UserProvided) | Az Aspose.Slides a [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) hivatkozásban a felhasználó által biztosított bájt tömböt használja képadatként. |
### Default {#Default}
```
public static final int Default
```

Az Aspose.Slides a szokásos módon tölti be a külső erőforrást.

### Skip {#Skip}
```
public static final int Skip
```

Az Aspose.Slides kihagyja a külső erőforrás betöltését. Csak a hivatkozás adat nélkül kerül tárolásra egy képhez.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Az Aspose.Slides a [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) hivatkozásban a felhasználó által biztosított bájt tömböt használja képadatként.
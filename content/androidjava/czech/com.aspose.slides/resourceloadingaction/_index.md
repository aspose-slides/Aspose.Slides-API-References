---
title: ResourceLoadingAction
second_title: Aspose.Slides pro Android přes Java API Reference
description: Určuje režim načítání externího zdroje.
type: docs
url: /cs/com.aspose.slides/resourceloadingaction/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Určuje režim načítání externího zdroje.
## Pole

| Pole | Popis |
| --- | --- |
| [Default](#Default) | Aspose.Slides načte externí zdroj jako obvykle. |
| [Skip](#Skip) | Aspose.Slides přeskočí načítání externího zdroje. |
| [UserProvided](#UserProvided) | Aspose.Slides použije pole bytů poskytnuté uživatelem v [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) jako data obrázku. |
### Default {#Default}
```
public static final int Default
```


Aspose.Slides načte externí zdroj jako obvykle.

### Skip {#Skip}
```
public static final int Skip
```


Aspose.Slides přeskočí načítání externího zdroje. Pouze odkaz bez dat bude uložen pro obrázek.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```


Aspose.Slides použije pole bytů poskytnuté uživatelem v [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) jako data obrázku.
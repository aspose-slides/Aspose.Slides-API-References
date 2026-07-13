---
title: ResourceLoadingAction
second_title: Aspose.Slides för Android via Java API-referens
description: Anger läget för laddning av externa resurser.
type: docs
url: /sv/com.aspose.slides/resourceloadingaction/
---
**Arv:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Anger läget för laddning av externa resurser.
## Fält

| Field | Description |
| --- | --- |
| [Default](#Default) | Aspose.Slides kommer att ladda extern resurs som vanligt. |
| [Skip](#Skip) | Aspose.Slides kommer att hoppa över laddning av extern resurs. |
| [UserProvided](#UserProvided) | Aspose.Slides kommer att använda bytearray som tillhandahålls av användaren i [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) som bilddata. |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides kommer att ladda extern resurs som vanligt.

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides kommer att hoppa över laddning av extern resurs. Endast en länk utan data kommer att lagras för en bild.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides kommer att använda bytearray som tillhandahålls av användaren i [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) som bilddata.
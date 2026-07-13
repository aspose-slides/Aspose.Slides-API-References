---
title: ResourceLoadingAction
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Określa tryb ładowania zasobów zewnętrznych.
type: docs
url: /pl/com.aspose.slides/resourceloadingaction/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Określa tryb ładowania zasobów zewnętrznych.
## Pola

| Pole | Opis |
| --- | --- |
| [Default](#Default) | Aspose.Slides załaduje zasób zewnętrzny w sposób standardowy. |
| [Skip](#Skip) | Aspose.Slides pominie ładowanie zasobu zewnętrznego. |
| [UserProvided](#UserProvided) | Aspose.Slides użyje tablicy bajtów dostarczonej przez użytkownika w [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) jako danych obrazu. |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides załaduje zasób zewnętrzny w sposób standardowy.

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides pominie ładowanie zasobu zewnętrznego. Tylko link bez danych zostanie zapisany dla obrazu.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides użyje tablicy bajtów dostarczonej przez użytkownika w [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) jako danych obrazu.
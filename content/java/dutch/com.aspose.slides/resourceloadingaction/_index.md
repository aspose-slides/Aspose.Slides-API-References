---
title: ResourceLoadingAction
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert de modus van het laden van externe bronnen.
type: docs
url: /nl/com.aspose.slides/resourceloadingaction/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Specificeert de modus van het laden van externe bronnen.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Default](#Default) | Aspose.Slides laadt de externe bron zoals gebruikelijk. |
| [Skip](#Skip) | Aspose.Slides slaat het laden van de externe bron over. |
| [UserProvided](#UserProvided) | Aspose.Slides gebruikt de door de gebruiker geleverde byte array in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) als afbeeldingsgegevens. |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides laadt de externe bron zoals gebruikelijk.

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides slaat het laden van de externe bron over. Alleen een link zonder gegevens wordt opgeslagen voor een afbeelding.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides gebruikt de door de gebruiker geleverde byte array in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) als afbeeldingsgegevens.
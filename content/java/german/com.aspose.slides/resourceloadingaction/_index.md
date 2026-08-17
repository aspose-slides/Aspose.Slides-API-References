---
title: ResourceLoadingAction
second_title: Aspose.Slides für Java API Referenz
description: Gibt den Modus des Ladens externer Ressourcen an.
type: docs
url: /de/com.aspose.slides/resourceloadingaction/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Gibt den Modus des Ladens externer Ressourcen an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Default](#Default) | Aspose.Slides wird die externe Ressource wie üblich laden. |
| [Skip](#Skip) | Aspose.Slides überspringt das Laden der externen Ressource. |
| [UserProvided](#UserProvided) | Aspose.Slides verwendet das vom Benutzer bereitgestellte Byte-Array in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) als Bilddaten. |
### Default {#Default}
```
public static final int Default
```


Aspose.Slides wird die externe Ressource wie üblich laden.

### Skip {#Skip}
```
public static final int Skip
```


Aspose.Slides überspringt das Laden der externen Ressource. Nur ein Link ohne Daten wird für ein Bild gespeichert.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```


Aspose.Slides verwendet das vom Benutzer bereitgestellte Byte-Array in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) als Bilddaten.
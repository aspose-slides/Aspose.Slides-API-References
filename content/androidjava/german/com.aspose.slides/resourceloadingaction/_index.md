---
title: ResourceLoadingAction
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Gibt den Modus des Ladens externer Ressourcen an.
type: docs
url: /de/com.aspose.slides/resourceloadingaction/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Specifiziert den Modus des Ladens externer Ressourcen.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Default](#Default) | Aspose.Slides wird externe Ressource wie üblich laden. |
| [Skip](#Skip) | Aspose.Slides wird das Laden externer Ressourcen überspringen. |
| [UserProvided](#UserProvided) | Aspose.Slides wird das vom Benutzer bereitgestellte Byte-Array in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) als Bilddaten verwenden. |
### Standard {#Default}
```
public static final int Default
```

Aspose.Slides wird externe Ressource wie üblich laden.

### Überspringen {#Skip}
```
public static final int Skip
```

Aspose.Slides wird das Laden der externen Ressource überspringen. Nur ein Link ohne Daten wird für ein Bild gespeichert.

### Benutzerbereitgestellt {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides wird das vom Benutzer bereitgestellte Byte-Array in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) als Bilddaten verwenden.
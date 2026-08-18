---
title: LinkEmbedDecision
second_title: Aspose.Slides für Java API Referenz
description: Bestimmt, wie das Objekt beim Speichern verarbeitet wird.
type: docs
url: /de/com.aspose.slides/linkembeddecision/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Bestimmt, wie das Objekt beim Speichern verarbeitet wird.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Link](#Link) | Objekt wird extern gespeichert und per URL referenziert |
| [Embed](#Embed) | Objekt sollte, wenn möglich, in eine erzeugte Datei eingebettet werden. |
| [Ignore](#Ignore) | Objekt wird ignoriert. |
### Verknüpfung {#Link}
```
public static final int Link
```

Objekt wird extern gespeichert und per URL referenziert

### Einbetten {#Embed}
```
public static final int Embed
```

Objekt sollte, wenn möglich, in eine erzeugte Datei eingebettet werden. Wenn das Einbetten nicht möglich ist, wird GetUrl aufgerufen und je nach Ergebnis wird das Objekt per URL referenziert oder ignoriert.

### Ignorieren {#Ignore}
```
public static final int Ignore
```

Objekt wird ignoriert.
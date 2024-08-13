---
title: EmbeddingLevel
second_title: Aspose.Slides for Java API Reference
description: Represents the licensing rights for embedding the font.
type: docs
url: /com.aspose.slides/embeddinglevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Represents the licensing rights for embedding the font.
## Fields

| Field | Description |
| --- | --- |
| [Installable](#Installable) | Fonts with this setting indicate that they may be embedded and permanently installed on the remote system by an application. |
| [Restricted](#Restricted) | Fonts that have only this bit set must not be modified, embedded or exchanged in any manner without first obtaining permission of the legal owner. |
| [PreviewPrint](#PreviewPrint) | When this bit is set, the font may be embedded, and temporarily loaded on the remote system. |
| [Editable](#Editable) | When this bit is set, the font may be embedded but must only be installed temporarily on other systems. |
| [NoSubsetting](#NoSubsetting) | When this bit is set, the font may not be subsetted prior to embedding. |
| [BitmapOnly](#BitmapOnly) | When this bit is set, only bitmaps contained in the font may be embedded. |
### Installable {#Installable}
```
public static final int Installable
```


Fonts with this setting indicate that they may be embedded and permanently installed on the remote system by an application. The user of the remote system acquires the identical rights, obligations and licenses for that font as the original purchaser of the font, and is subject to the same end-user license agreement, copyright, design patent, and/or trademark as was the original purchaser.

### Restricted {#Restricted}
```
public static final int Restricted
```


Fonts that have only this bit set must not be modified, embedded or exchanged in any manner without first obtaining permission of the legal owner.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```


When this bit is set, the font may be embedded, and temporarily loaded on the remote system. Documents containing Preview & Print fonts must be opened "read-only;" no edits can be applied to the document.

### Editable {#Editable}
```
public static final int Editable
```


When this bit is set, the font may be embedded but must only be installed temporarily on other systems. In contrast to Preview & Print fonts, documents containing Editable fonts may be opened for reading, editing is permitted, and changes may be saved.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```


When this bit is set, the font may not be subsetted prior to embedding. Other embedding restrictions specified in bits 0-3 and 9 also apply.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```


When this bit is set, only bitmaps contained in the font may be embedded. No outline data may be embedded. If there are no bitmaps available in the font, then the font is considered unembeddable and the embedding services will fail.


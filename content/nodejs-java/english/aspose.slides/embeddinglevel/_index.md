---
title: EmbeddingLevel
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/embeddinglevel/
---

## EmbeddingLevel class

 Represents the licensing rights for embedding the font.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
[Installable](#Installable) | 0 | Fonts with this setting indicate that they may be embedded and permanently installed on the remote system by an application. The user of the remote system acquires the identical rights, obligations and licenses for that font as the original purchaser of the font, and is subject to the same end-user license agreement, copyright, design patent, and/or trademark as was the original purchaser. |
[Restricted](#Restricted) | 2 | Fonts that have only this bit set must not be modified, embedded or exchanged in any manner without first obtaining permission of the legal owner. |
[PreviewPrint](#PreviewPrint) | 4 | When this bit is set, the font may be embedded, and temporarily loaded on the remote system. Documents containing Preview &amp; Print fonts must be opened "read-only;" no edits can be applied to the document. |
[Editable](#Editable) | 8 | When this bit is set, the font may be embedded but must only be installed temporarily on other systems. In contrast to Preview &amp; Print fonts, documents containing Editable fonts may be opened for reading, editing is permitted, and changes may be saved. |
[NoSubsetting](#NoSubsetting) | 256 | When this bit is set, the font may not be subsetted prior to embedding. Other embedding restrictions specified in bits 0-3 and 9 also apply. |
[BitmapOnly](#BitmapOnly) | 512 | When this bit is set, only bitmaps contained in the font may be embedded. No outline data may be embedded. If there are no bitmaps available in the font, then the font is considered unembeddable and the embedding services will fail. |


---


### Installable {#Installable}
Fonts with this setting indicate that they may be embedded and permanently installed on the remote system by an application. The user of the remote system acquires the identical rights, obligations and licenses for that font as the original purchaser of the font, and is subject to the same end-user license agreement, copyright, design patent, and/or trademark as was the original purchaser.

---

### Restricted {#Restricted}
Fonts that have only this bit set must not be modified, embedded or exchanged in any manner without first obtaining permission of the legal owner.

---

### PreviewPrint {#PreviewPrint}
When this bit is set, the font may be embedded, and temporarily loaded on the remote system. Documents containing Preview &amp; Print fonts must be opened "read-only;" no edits can be applied to the document.

---

### Editable {#Editable}
When this bit is set, the font may be embedded but must only be installed temporarily on other systems. In contrast to Preview &amp; Print fonts, documents containing Editable fonts may be opened for reading, editing is permitted, and changes may be saved.

---

### NoSubsetting {#NoSubsetting}
When this bit is set, the font may not be subsetted prior to embedding. Other embedding restrictions specified in bits 0-3 and 9 also apply.

---

### BitmapOnly {#BitmapOnly}
When this bit is set, only bitmaps contained in the font may be embedded. No outline data may be embedded. If there are no bitmaps available in the font, then the font is considered unembeddable and the embedding services will fail.

---



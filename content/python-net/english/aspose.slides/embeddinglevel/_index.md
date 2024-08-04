---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/embeddinglevel/
---


## EmbeddingLevel enumeration

Represents the licensing rights for embedding the font.

The EmbeddingLevel type exposes the following members:

## Fields

| Field | Description |
| :- | :- |
| INSTALLABLE | Fonts with this setting indicate that they may be embedded and permanently installed on the remote system by an application. <br/>            The user of the remote system acquires the identical rights, obligations and licenses for that font as the original purchaser of the font, <br/>            and is subject to the same end-user license agreement, copyright, design patent, and/or trademark as was the original purchaser. |
| RESTRICTED | Fonts that have only this bit set must not be modified, embedded or exchanged in any manner without first obtaining permission of the legal owner. |
| PREVIEW_PRINT | When this bit is set, the font may be embedded, and temporarily loaded on the remote system. Documents containing Preview & <br/>            Print fonts must be opened "read-only;" no edits can be applied to the document. |
| EDITABLE | When this bit is set, the font may be embedded but must only be installed temporarily on other systems. In contrast to Preview & <br/>            Print fonts, documents containing Editable fonts may be opened for reading, editing is permitted, and changes may be saved. |
| NO_SUBSETTING | When this bit is set, the font may not be subsetted prior to embedding. Other embedding restrictions specified in bits 0-3 and 9 also apply. |
| BITMAP_ONLY | When this bit is set, only bitmaps contained in the font may be embedded. No outline data may be embedded. If there are no bitmaps available in the font, <br/>            then the font is considered unembeddable and the embedding services will fail. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)


---
title: GetThumbnailImage()
second_title: Aspose.Slides C++ API-referencia
description: "Lekér egy bélyegképet ehhez a System::Drawing::Image objektumhoz."
type: docs
weight: 326
url: /hu/system.drawing/image/getthumbnailimage/
---
## Image::GetThumbnailImage(int, int, Image::GetThumbnailImageAbort, IntPtr) metódus

Lekér egy bélyegképet ehhez a [System::Drawing::Image](../) objektumhoz.

```cpp
SharedPtr<Image> System::Drawing::Image::GetThumbnailImage(int thumbWidth, int thumbHeight, Image::GetThumbnailImageAbort callback, IntPtr callbackData)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| thumbWidth | int | A bélyegkép szélessége |
| thumbHeight | int | A bélyegkép magassága |
| callback | [Image::GetThumbnailImageAbort](../getthumbnailimageabort/) | Mellőzve |
| callbackData | IntPtr | Mellőzve |

### Visszatérési érték

Egy bélyegkép ehhez a [System::Drawing::Image](../) objektumhoz

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [GetThumbnailImageAbort](../getthumbnailimageabort/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
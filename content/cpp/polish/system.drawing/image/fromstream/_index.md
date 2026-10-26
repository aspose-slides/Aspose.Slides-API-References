---
title: FromStream()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Tworzy obiekt Image z określonego strumienia.
type: docs
weight: 339
url: /pl/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) metoda

Tworzy obiekt [Image](../) z określonego strumienia.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Strumień zawierający dane obrazu |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### Wartość zwracana

Wskaźnik współdzielony do utworzonego obiektu [Image](../).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Image](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)
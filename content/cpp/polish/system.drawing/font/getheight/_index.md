---
title: GetHeight()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca odstęp linii czcionki reprezentowanej przez bieżący obiekt, w bieżącej jednostce określonego obiektu Graphics.
type: docs
weight: 14
url: /pl/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) metoda

Zwraca odstęp linii czcionki reprezentowanej przez bieżący obiekt, w bieżącej jednostce określonego obiektu [Graphics](../../graphics/).

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Obiekt [Graphics](../../graphics/), który określa jednostki miary |

## Font::GetHeight(float) metoda

Zwraca wysokość czcionki reprezentowanej przez bieżący obiekt, gdy jest rysowana na urządzeniu wyświetlającym z określoną rozdzielczością pionową.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dpi | **float** | Rozdzielczość pionowa urządzenia wyświetlającego |

### Wartość zwracana

Wysokość czcionki w pikselach

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Graphics](../../graphics/)
* Klasa [Font](../)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)
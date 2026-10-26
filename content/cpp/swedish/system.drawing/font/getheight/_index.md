---
title: GetHeight()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar radavståndet för det teckensnitt som representeras av det aktuella objektet, i den aktuella enheten för ett specificerat Graphics-objekt.
type: docs
weight: 14
url: /sv/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) metod

Returnerar radavståndet för det teckensnitt som representeras av det aktuella objektet, i den aktuella enheten för ett specificerat [Graphics](../../graphics/)-objekt.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Ett [Graphics](../../graphics/)-objekt som specificerar mätenheterna |

## Font::GetHeight(float) metod

Returnerar höjden på det teckensnitt som representeras av det aktuella objektet när det ritas på en displayenhet med den specificerade vertikala upplösningen.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpi | **float** | Den vertikala upplösningen av displayenheten |

### Returvärde

Fontens höjd i pixlar

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Graphics](../../graphics/)
* Klass [Font](../)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)
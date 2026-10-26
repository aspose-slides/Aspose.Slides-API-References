---
title: MathF
second_title: Aspose.Slides för C++ API-referens
description: Innehåller matematiska funktioner för värden med enkelprecisions-flyttal. Detta är en statisk typ utan instansmetoder. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 1795
url: /sv/system/mathf/
---
## MathF struct

Innehåller matematiska funktioner för värden med enkelprecisions-flyttal. Detta är en statisk typ utan instansmetoder. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class MathF
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static T [Abs](./abs/)(T) | Returnerar det absoluta värdet av det angivna värdet. |
| static **float** [Acos](./acos/)(**float**) | Beräknar arccosinus av det angivna värdet. |
| static **float** [Asin](./asin/)(**float**) | Beräknar arcsinus av det angivna värdet. |
| static **float** [Atan](./atan/)(**float**) | Beräknar arctan av det angivna värdet. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Beräknar arctan av förhållandet mellan de angivna värdena. |
| static **float** [Ceiling](./ceiling/)(**float**) | Returnerar det minsta heltalsvärdet som är större än eller lika med det angivna värdet. |
| static **float** [Cos](./cos/)(**float**) | Beräknar cosinus av det angivna värdet. |
| static **float** [Cosh](./cosh/)(**float**) | Beräknar hyperbolisk cosinus av det angivna värdet. |
| static **float** [Exp](./exp/)(**float**) | Returnerar e-konstanten upphöjd till den angivna potensen. |
| static **float** [Floor](./floor/)(**float**) | Returnerar det största heltalsvärdet som är mindre än eller lika med det angivna värdet. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Returnerar resten som erhålls vid divisionen av ett angivet tal med ett annat angivet tal. |
| static **float** [Log](./log/)(**float**) | Returnerar den naturliga logaritmen för det angivna värdet. |
| static **float** [Log](./log/)(**float**, **float**) | Returnerar logaritmen för det angivna värdet i den angivna basen. |
| static **float** [Log10](./log10/)(**float**) | Returnerar bas-10-logaritmen för det angivna värdet. |
| static **float** [Pow](./pow/)(**float**, **float**) | Returnerar det angivna värdet upphöjt till den angivna potensen. |
| static **float** [Round](./round/)(**float**) | Avrundar det angivna värdet till närmaste heltal. |
| static **float** [Round](./round/)(**float**, int) | Avrundar det angivna värdet till närmaste värde med det angivna antalet decimaler. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Avrundar det angivna värdet till närmaste heltal. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Avrundar det angivna värdet till närmaste värde med det angivna antalet decimaler. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Avrundar det angivna värdet till närmaste värde med det angivna antalet decimaler. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Bestämmer tecknet på det angivna signerade heltalsvärdet. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Bestämmer tecknet på det angivna flyttalvärdet. |
| static **float** [Sin](./sin/)(**float**) | Beräknar sinus av det angivna värdet. |
| static **float** [Sinh](./sinh/)(**float**) | Beräknar hyperbolisk sinus av det angivna värdet. |
| static **float** [Sqrt](./sqrt/)(**float**) | Returnerar kvadratroten av det angivna värdet. |
| static **float** [Tan](./tan/)(**float**) | Beräknar tangenten av det angivna värdet. |
| static **float** [Tanh](./tanh/)(**float**) | Beräknar hyperbolisk tangent av det angivna värdet. |
| static **float** [Truncate](./truncate/)(**float**) | Returnerar ett flyttal med enkelprecision vars heltalsdel är lika med den angivna värdets heltalsdel, med alla decimaler borttagna. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [E](./e/) | Basen för den naturliga logaritmen. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | Pi-konstanten. |
| static [Tau](./tau/) | Tau-värdet. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)
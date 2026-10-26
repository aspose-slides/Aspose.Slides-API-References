---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides dla Pythona przez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enumeracja

Definiuje operację transformacji koloru.

Typ ColorTransformOperation udostępnia następujące elementy:

## Pola

| Pole | Opis |
| :- | :- |
| TINT | Nadanie odcienia kolorowi. Parametr mieści się w przedziale od 0 (oryginalny kolor) do 1 (biały). |
| SHADE | Przyciemnienie koloru. Parametr mieści się w przedziale od 0 (oryginalny kolor) do 1 (czarny). |
| COMPLEMENT | Zmienia kolor na uzupełniający w RGB.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Zmienia kolor na odwrócony.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Zmienia kolor na szary o tej samej jasności. Parametr jest ignorowany. |
| SET_ALPHA | Definiuje komponent alfa koloru. Parametr mieści się w przedziale od 0 (przezroczysty) do 1 (nieprzezroczysty). |
| ADD_ALPHA | Dodaje wartość parametru do komponentu alfa koloru. Parametr mieści się w przedziale od -1 do 1. |
| MULTIPLY_ALPHA | Mnoży komponent alfa przez wartość parametru. |
| SET_HUE | Zmienia komponent odcienia (hue) koloru na wartość parametru. Parametr mieści się w przedziale od 0 do 360. |
| ADD_HUE | Dodaje wartość parametru do komponentu odcienia koloru. Parametr mieści się w przedziale od -360 do 360. |
| MULTIPLY_HUE | Mnoży komponent odcienia przez wartość parametru. |
| SET_SATURATION | Zmienia komponent nasycenia koloru na wartość parametru. Parametr mieści się w przedziale od 0 do 1. |
| ADD_SATURATION | Dodaje wartość parametru do komponentu nasycenia koloru. Parametr mieści się w przedziale od -1 do 1. |
| MULTIPLY_SATURATION | Mnoży komponent nasycenia przez wartość parametru. |
| SET_LUMINANCE | Zmienia komponent luminancji koloru na wartość parametru. Parametr mieści się w przedziale od 0 do 1. |
| ADD_LUMINANCE | Dodaje wartość parametru do komponentu luminancji koloru. Parametr mieści się w przedziale od -1 do 1. |
| MULTIPLY_LUMINANCE | Mnoży komponent luminancji przez wartość parametru. |
| SET_RED | Zmienia czerwony komponent koloru na wartość parametru. Parametr mieści się w przedziale od 0 do 1. |
| ADD_RED | Dodaje wartość parametru do czerwonego komponentu koloru. Parametr mieści się w przedziale od -1 do 1. |
| MULTIPLY_RED | Mnoży czerwony komponent przez parametr. |
| SET_GREEN | Zmienia zielony komponent koloru na wartość parametru. Parametr mieści się w przedziale od 0 do 1. |
| ADD_GREEN | Dodaje parametr do zielonego komponentu koloru. Parametr mieści się w przedziale od -1 do 1. |
| MULTIPLY_GREEN | Mnoży zielony komponent koloru przez wartość parametru. |
| SET_BLUE | Zmienia niebieski komponent koloru na wartość parametru. Parametr mieści się w przedziale od 0 do 360. |
| ADD_BLUE | Dodaje wartość parametru do niebieskiego komponentu koloru. Parametr mieści się w przedziale od -1 do 1. |
| MULTIPLY_BLUE | Mnoży niebieski komponent przez wartość parametru. |
| GAMMA | Korekcja gamma. Parametr jest ignorowany. |
| INVERSE_GAMMA | Odwrócona korekcja gamma. Parametr jest ignorowany. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)
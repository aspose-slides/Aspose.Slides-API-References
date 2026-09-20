---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/colortransformoperation/
---
## ColorTransformOperation uppräkning

Definierar färgtransformationsåtgärd.

Typen ColorTransformOperation exponerar följande medlemmar:

## Fält

| Fält | Beskrivning |
| :- | :- |
| TINT | Färgar färgen. Parametern är i intervallet mellan 0 (original färg) och 1 (vit). |
| SHADE | Tonar färgen. Parametern är i intervallet mellan 0 (original färg) och 1 (svart). |
| COMPLEMENT | Ändrar färgen till en RGB-komplementär färg.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Ändrar färgen till en inverterad färg.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Ändrar färgen till en grå nyans med samma ljusstyrka. Parametern ignoreras. |
| SET_ALPHA | Definierar en alfa-komponent för färgen. Parametern är i intervallet mellan 0 (transparent) och 1 (opak). |
| ADD_ALPHA | Lägger till parametervärdet till en alfa-komponent för färgen. Parametern är i intervallet mellan -1 och 1. |
| MULTIPLY_ALPHA | Multiplicerar en alfa-komponent med ett parametervärde. |
| SET_HUE | Ändrar färgens nyanskomponent till ett parametervärde. Parametern är i intervallet mellan 0 och 360. |
| ADD_HUE | Lägger till parametervärdet till färgens nyanskomponent. Parametern är i intervallet mellan -360 och 360. |
| MULTIPLY_HUE | Multiplicerar färgens nyanskomponent med ett parametervärde. |
| SET_SATURATION | Ändrar färgens mättnadskomponent till ett parametervärde. Parametern är i intervallet mellan 0 och 1. |
| ADD_SATURATION | Lägger till ett parametervärde till färgens mättnadskomponent. Parametern är i intervallet mellan -1 och 1. |
| MULTIPLY_SATURATION | Multiplicerar färgens mättnadskomponent med ett parametervärde. |
| SET_LUMINANCE | Ändrar färgens luminanskomponent till ett parametervärde. Parametern är i intervallet mellan 0 och 1. |
| ADD_LUMINANCE | Lägger till ett parametervärde till färgens luminanskomponent. Parametern är i intervallet mellan -1 och 1. |
| MULTIPLY_LUMINANCE | Multiplicerar färgens luminanskomponent med ett parametervärde. |
| SET_RED | Ändrar färgens röda komponent till ett parametervärde. Parametern är i intervallet mellan 0 och 1. |
| ADD_RED | Lägger till ett parametervärde till färgens röda komponent. Parametern är i intervallet mellan -1 och 1. |
| MULTIPLY_RED | Multiplicerar färgens röda komponent med ett parametervärde. |
| SET_GREEN | Ändrar färgens gröna komponent till ett parametervärde. Parametern är i intervallet mellan 0 och 1. |
| ADD_GREEN | Lägger till ett parametervärde till färgens gröna komponent. Parametern är i intervallet mellan -1 och 1. |
| MULTIPLY_GREEN | Multiplicerar färgens gröna komponent med ett parametervärde. |
| SET_BLUE | Ändrar färgens blå komponent till ett parametervärde. Parametern är i intervallet mellan 0 och 360. |
| ADD_BLUE | Lägger till ett parametervärde till färgens blå komponent. Parametern är i intervallet mellan -1 och 1. |
| MULTIPLY_BLUE | Multiplicerar färgens blå komponent med ett parametervärde. |
| GAMMA | Gamma-korrektion. Parametern ignoreras. |
| INVERSE_GAMMA | Invers gamma-korrektion. Parametern ignoreras. |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)
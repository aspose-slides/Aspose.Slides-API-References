---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/colortransformoperation/
---
## Výčtový typ ColorTransformOperation

Definuje operaci transformace barvy.

Typ ColorTransformOperation obsahuje následující členy:

## Pole

| Pole | Popis |
| :- | :- |
| TINT | Upravuje odstín barvy. Parametr je v rozmezí od 0 (originální barva) do 1 (bílá). |
| SHADE | Stínuje barvu. Parametr je v rozmezí od 0 (originální barva) do 1 (černá). |
| COMPLEMENT | Mění barvu na RGB komplementární.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Mění barvu na inverzní barvu.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Mění barvu na šedou se stejnou jasností. Parametr je ignorován. |
| SET_ALPHA | Definuje alfa komponentu barvy. Parametr je v rozmezí od 0 (průhledná) do 1 (neprůhledná). |
| ADD_ALPHA | Přidává hodnotu parametru k alfa komponentě barvy. Parametr je v rozmezí od -1 do 1. |
| MULTIPLY_ALPHA | Násobí alfa komponentu hodnotou parametru. |
| SET_HUE | Mění komponentu odstínu barvy na hodnotu parametru. Parametr je v rozmezí od 0 do 360. |
| ADD_HUE | Přidává hodnotu parametru k komponentě odstínu barvy. Parametr je v rozmezí od -360 do 360. |
| MULTIPLY_HUE | Násobí komponentu odstínu hodnotou parametru. |
| SET_SATURATION | Mění komponentu sytosti barvy na hodnotu parametru. Parametr je v rozmezí od 0 do 1. |
| ADD_SATURATION | Přidává hodnotu parametru k komponentě sytosti barvy. Parametr je v rozmezí od -1 do 1. |
| MULTIPLY_SATURATION | Násobí komponentu sytosti hodnotou parametru. |
| SET_LUMINANCE | Mění komponentu jasu barvy na hodnotu parametru. Parametr je v rozmezí od 0 do 1. |
| ADD_LUMINANCE | Přidává hodnotu parametru k komponentě jasu barvy. Parametr je v rozmezí od -1 do 1. |
| MULTIPLY_LUMINANCE | Násobí komponentu jasu hodnotou parametru. |
| SET_RED | Mění červenou komponentu barvy na hodnotu parametru. Parametr je v rozmezí od 0 do 1. |
| ADD_RED | Přidává hodnotu parametru k červené komponentě barvy. Parametr je v rozmezí od -1 do 1. |
| MULTIPLY_RED | Násobí červenou komponentu parametrem. |
| SET_GREEN | Mění zelenou komponentu barvy na hodnotu parametru. Parametr je v rozmezí od 0 do 1. |
| ADD_GREEN | Přidává parametr k zelené komponentě barvy. Parametr je v rozmezí od -1 do 1. |
| MULTIPLY_GREEN | Násobí zelenou komponentu hodnotou parametru. |
| SET_BLUE | Mění modrou komponentu barvy na hodnotu parametru. Parametr je v rozmezí od 0 do 360. |
| ADD_BLUE | Přidává hodnotu parametru k modré komponentě barvy. Parametr je v rozmezí od -1 do 1. |
| MULTIPLY_BLUE | Násobí modrou komponentu hodnotou parametru. |
| GAMMA | Gamma korekce. Parametr je ignorován. |
| INVERSE_GAMMA | Inverzní gamma korekce. Parametr je ignorován. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)
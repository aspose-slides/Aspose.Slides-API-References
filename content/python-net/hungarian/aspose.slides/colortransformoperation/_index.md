---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/colortransformoperation/
---
## ColorTransformOperation enumeráció

Meghatározza a színtranszformáció műveletét.

A ColorTransformOperation típus a következő tagokat teszi elérhetővé:

## Mezők

| Field | Description |
| :- | :- |
| TINT | A színt árnyékolja. A paraméter 0 (eredeti szín) és 1 (fehér) között van. |
| SHADE | Árnyékot ad a színnek. A paraméter 0 (eredeti szín) és 1 (fekete) között van. |
| COMPLEMENT | A színt RGB komplementer színre módosítja.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | A színt invertált színre változtatja.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | A színt szürke színre változtatja ugyanazzal a fényerővel. A paraméter figyelmen kívül marad. |
| SET_ALPHA | Meghatároz egy alfa komponenst a színben. A paraméter 0 (átlátszó) és 1 (átláthatatlan) között van. |
| ADD_ALPHA | A paraméter értékét hozzáadja a szín alfa komponenséhez. A paraméter -1 és 1 között van. |
| MULTIPLY_ALPHA | Az alfa komponenst megszorozza a paraméter értékével. |
| SET_HUE | A szín árnyalat (hue) komponensét a paraméter értékére változtatja. A paraméter 0 és 360 között van. |
| ADD_HUE | A paraméter értékét hozzáadja a szín árnyalat komponenséhez. A paraméter -360 és 360 között van. |
| MULTIPLY_HUE | Az árnyalat komponenst megszorozza a paraméter értékével. |
| SET_SATURATION | A szín telítettség komponensét a paraméter értékére állítja. A paraméter 0 és 1 között van. |
| ADD_SATURATION | A paraméter értékét hozzáadja a szín telítettség komponenséhez. A paraméter -1 és 1 között van. |
| MULTIPLY_SATURATION | A telítettség komponenst megszorozza a paraméter értékével. |
| SET_LUMINANCE | A szín fényesség (luminance) komponensét a paraméter értékére állítja. A paraméter 0 és 1 között van. |
| ADD_LUMINANCE | A paraméter értékét hozzáadja a szín fényesség komponenséhez. A paraméter -1 és 1 között van. |
| MULTIPLY_LUMINANCE | A fényesség komponenst megszorozza a paraméter értékével. |
| SET_RED | A szín piros komponensét a paraméter értékére állítja. A paraméter 0 és 1 között van. |
| ADD_RED | A paraméter értékét hozzáadja a szín piros komponenséhez. A paraméter -1 és 1 között van. |
| MULTIPLY_RED | A piros komponenst megszorozza a paraméterrel. |
| SET_GREEN | A szín zöld komponensét a paraméter értékére értékére állítja. A paraméter 0 és 1 között van. |
| ADD_GREEN | A paramétert hozzáadja a szín zöld komponenséhez. A paraméter -1 és 1 között van. |
| MULTIPLY_GREEN | A zöld komponenst megszorozza a paraméter értékével. |
| SET_BLUE | A szín kék komponensét a paraméter értékére állítja. A paraméter 0 és 360 között van. |
| ADD_BLUE | A paraméter értékét hozzáadja a szín kék komponenséhez. A paraméter -1 és 1 között van. |
| MULTIPLY_BLUE | A kék komponenst megszorozza a paraméter értékével. |
| GAMMA | Gamma korrekció. A paraméter figyelmen kívül marad. |
| INVERSE_GAMMA | Inverz gamma korrekció. A paraméter figyelmen kívül marad. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)
---
title: ShapeElement class
second_title: Aspose.Slides Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/shapeelement/
---
## ShapeElement osztály

A ShapeElement egy alakzat olyan részét képviseli, amelynek a körvonal és a kitöltés tulajdonságai megegyeznek.

A ShapeElement típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`parent_shape`](/slides/python-net/hu/aspose.slides/shapeelement/parent_shape/) | Visszaad egy Shape_PPT-t, amelyhez az elem létre lett hozva.<br/>            Csak olvasható [`Shape`](/slides/python-net/hu/aspose.slides/shape). |
| [`path_points`](/slides/python-net/hu/aspose.slides/shapeelement/path_points/) | Lekéri a pontok tömbjét, amely meghatározza az elem útvonalának geometriáját. |
| [`path_types`](/slides/python-net/hu/aspose.slides/shapeelement/path_types/) | Kapsz egy bájt értékek tömbjét, amely meghatározza az egyes pontok típusát az elem útvonalában. <br/>            <br/>**0**  A pont egy ábra kezdetét jelzi.<br/><br/><br/>**1**  A pont egy vonal két végpontjának egyike.<br/><br/><br/>**3**  A pont egy végpont vagy vezérlőpont egy köbös Bézier-görbében.<br/><br/><br/>**7**  Maszkolja az összes bitet, kivéve a három alacsonyabb rendű bitet, amelyek a pont típusát jelzik.<br/><br/><br/>**16**  A megfelelő szegmens szaggatott.<br/><br/><br/>**32**  A pont egy jelző.<br/><br/><br/>**128**  A pont az zárt alútra (ábra) vonatkozó utolsó pont.<br/><br/><br/>**129**  Olyan adatpont, amely egyszerre vonal szegmens végpont és egy zárt alútra utolsó pont. |
| [`fill_source`](/slides/python-net/hu/aspose.slides/shapeelement/fill_source/) | Visszaad információt arról, hogyan kell kitölteni egy elemet.<br/>            Csak olvasható [`ShapeElementFillSource`](/slides/python-net/hu/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/hu/aspose.slides/shapeelement/stroke_source/) | Visszaad információt arról, hogyan kell körvonalazni egy elemet.<br/>            Csak olvasható [`ShapeElementStrokeSource`](/slides/python-net/hu/aspose.slides/shapeelementstrokesource). |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)
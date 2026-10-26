---
title: GetVisualBounds()
second_title: Aspose.Slides C++ API hivatkozás
description: A formából a megjelenített tartalom alapján számított vizuális határokat adja vissza.
type: docs
weight: 677
url: /hu/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() metódus


A forma megjelenített tartalma alapján számított vizuális határokat adja vissza.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```


### Visszatérési érték

Egy [System::Drawing::RectangleF](../../../system.drawing/rectanglef/), amely a forma vizuális határait jelöli a dia koordinátáiban.
## Megjegyzés


A visszaadott téglalap a forma ábrázolása során keletkezett összes tartalom tengelyre igazított határait ábrázolja a dia koordináta-terében.

Ezek a határok eltérhetnek a forma modellhatáraitól ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)), és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlnyúlik a dia eredetén.

A vizuális határok figyelembe veszik a rendereléshez kapcsolódó tényezőket, például a transzformációkat (például forgatás), a vonalvastagságot és illeszkedéseket, a szövegelrendezést és túlcsordulást, a [SmartArt](../../../aspose.slides.smartart/) geometriát, valamint a forma végső megjelenését befolyásoló egyéb elrendezési hatásokat.

A visszaadott határok nincsenek levágva a dia téglalapjára. 

## Lásd még

* Osztály [RectangleF](../../../system.drawing/rectanglef/)
* Osztály [Shape](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)
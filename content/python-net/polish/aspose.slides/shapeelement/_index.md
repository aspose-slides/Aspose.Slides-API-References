---
title: ShapeElement class
second_title: Aspose.Slides dla Pythona poprzez .NET - Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/shapeelement/
---
## ShapeElement klasa

Reprezentuje część kształtu o tych samych właściwościach konturu i wypełnienia.

Typ ShapeElement udostępnia następujące członki:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`parent_shape`](/slides/python-net/pl/aspose.slides/shapeelement/parent_shape/) | Zwraca obiekt Shape_PPT, dla którego element został utworzony.<br/>Tylko do odczytu [`Shape`](/slides/python-net/pl/aspose.slides/shape). |
| [`path_points`](/slides/python-net/pl/aspose.slides/shapeelement/path_points/) | Pobiera tablicę punktów definiujących geometrię ścieżki elementu. |
| [`path_types`](/slides/python-net/pl/aspose.slides/shapeelement/path_types/) | Pobiera tablicę wartości bajtowych określających typ każdego punktu w ścieżce elementu.<br/><br/>**0**  Oznacza, że punkt jest początkiem figury.<br/><br/>**1**  Oznacza, że punkt jest jednym z dwóch końcowych punktów linii.<br/><br/>**3**  Oznacza, że punkt jest końcowym lub kontrolnym punktem krzywej Beziera trzeciego stopnia.<br/><br/>**7**  Maskuje wszystkie bity oprócz trzech najmniej znaczących, które określają typ punktu.<br/><br/>**16**  Określa, że odpowiadający segment jest przerywany.<br/><br/>**32**  Określa, że punkt jest znacznikiem.<br/><br/>**128**  Określa, że punkt jest ostatnim punktem w zamkniętej podścieżce (figurze).<br/><br/>**129**  Oznacza punkt danych będący jednocześnie końcowym punktem segmentu linii i ostatnim punktem zamkniętej podścieżki. |
| [`fill_source`](/slides/python-net/pl/aspose.slides/shapeelement/fill_source/) | Zwraca informacje o tym, jak wypełnić element.<br/>Tylko do odczytu [`ShapeElementFillSource`](/slides/python-net/pl/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/pl/aspose.slides/shapeelement/stroke_source/) | Zwraca informacje o tym, jak narysować obrys elementu.<br/>Tylko do odczytu [`ShapeElementStrokeSource`](/slides/python-net/pl/aspose.slides/shapeelementstrokesource). |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)
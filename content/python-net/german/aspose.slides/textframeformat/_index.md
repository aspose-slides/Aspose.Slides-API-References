---
title: TextFrameFormat class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/textframeformat/
---
## TextFrameFormat Klasse

Enthält die Formatierungseigenschaften des TextFrames.

**Vererbung:**[`TextFrameFormat`](/slides/python-net/de/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/de/aspose.slides/pviobject)

Der Typ TextFrameFormat stellt die folgenden Member bereit:

## Konstruktoren

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides/textframeformat/__init__/#) | Initialisiert eine neue Instanz der [`TextFrameFormat`](/slides/python-net/de/aspose.slides/textframeformat) Klasse. |

## Eigenschaften

| Property | Description |
| :- | :- |
| [`three_d_format`](/slides/python-net/de/aspose.slides/textframeformat/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekteigenschaften für einen Text darstellt.<br/>            Nur lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/de/aspose.slides/textframeformat/margin_left/) | Gibt den linken Rand (Punkte) in einem TextFrame zurück oder setzt ihn.<br/>            Lese/Schreib **float**. |
| [`margin_right`](/slides/python-net/de/aspose.slides/textframeformat/margin_right/) | Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder setzt ihn.<br/>            Lese/Schreib **float**. |
| [`margin_top`](/slides/python-net/de/aspose.slides/textframeformat/margin_top/) | Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder setzt ihn.<br/>            Lese/Schreib **float**. |
| [`margin_bottom`](/slides/python-net/de/aspose.slides/textframeformat/margin_bottom/) | Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder setzt ihn.<br/>            Lese/Schreib **float**. |
| [`wrap_text`](/slides/python-net/de/aspose.slides/textframeformat/wrap_text/) | **True**  wenn Text an den Rändern des TextFrames umgebrochen wird.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/de/aspose.slides/textframeformat/anchoring_type/) | Gibt den vertikalen Ankertext in einem TextFrame zurück oder setzt ihn.<br/>            Lese/Schreib [`TextAnchorType`](/slides/python-net/de/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/de/aspose.slides/textframeformat/center_text/) | Wenn NullableBool.True, dann sollte der Text horizontal in der Box zentriert werden.<br/>            Lese/Schreib [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/de/aspose.slides/textframeformat/text_vertical_type/) | Bestimmt die Textausrichtung.<br/>            Der resultierende Wert der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle.<br/>            Lese/Schreib [`TextVerticalType`](/slides/python-net/de/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/de/aspose.slides/textframeformat/autofit_type/) | Gibt den Autofit-Modus des Textes zurück oder setzt ihn.<br/>            Lese/Schreib [`TextAutofitType`](/slides/python-net/de/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/de/aspose.slides/textframeformat/column_count/) | Gibt die Anzahl der Spalten im Textbereich zurück oder setzt sie.<br/>            Dieser Wert muss positiv sein. Andernfalls wird der Wert auf null gesetzt. <br/>            Wert 0 bedeutet undefinierten Wert.<br/>            Lese/Schreib **int**. |
| [`column_spacing`](/slides/python-net/de/aspose.slides/textframeformat/column_spacing/) | Gibt den Abstand zwischen Textspalten im Textbereich (in Punkten) zurück oder setzt ihn. Dies sollte nur gelten, <br/>            wenn mehr als eine Spalte vorhanden ist.<br/>            Dieser Wert muss positiv sein. Andernfalls wird der Wert auf null gesetzt. <br/>            Lese/Schreib **float**. |
| [`rotation_angle`](/slides/python-net/de/aspose.slides/textframeformat/rotation_angle/) | Gibt die benutzerdefinierte Rotation an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht<br/>            angegeben ist, wird die Rotation der zugehörigen Form verwendet. Wenn sie angegeben ist, wird sie unabhängig von der Form angewendet.<br/>            Das heißt, die Form kann eine Rotation haben, zusätzlich zur Rotation des Textes selbst.<br/>            Der resultierende Wert der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem vordefinierten<br/>            vertikalen Typ in der Eigenschaft TextVerticalType.<br/>            Lese/Schreib **float**. |
| [`transform`](/slides/python-net/de/aspose.slides/textframeformat/transform/) | Gibt die Textumbruch-Form zurück oder setzt sie.<br/>            Lese/Schreib [`TextShapeType`](/slides/python-net/de/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/de/aspose.slides/textframeformat/keep_text_flat/) | Gibt an, ob der Text flach bleibt, selbst wenn ein 3-D-Rotations-Effekt angewendet wurde.<br/>            Lese/Schreib **bool**. |
| [`slide`](/slides/python-net/de/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/de/aspose.slides/textframeformat/text_style/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/de/aspose.slides/textframeformat/get_effective/#) | Ruft die effektiven TextFrame-Formatierungsdaten mit angewandter Vererbung ab. |

### Siehe auch
* Klasse [`PVIObject`](/slides/python-net/de/aspose.slides/pviobject)
* Klasse [`TextFrameFormat`](/slides/python-net/de/aspose.slides/textframeformat)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)
---
title: ITextFrameFormat class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/itextframeformat/
---
## ITextFrameFormat Klasse

Contains the TextFrame's formatting properties.

The ITextFrameFormat type exposes the following members:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`text_style`](/slides/python-net/de/aspose.slides/itextframeformat/text_style/) | Gibt den Stil des Textes zurück.<br/>            Nur lesbar [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/de/aspose.slides/itextframeformat/margin_left/) | Gibt den linken Rand (Punkte) in einem TextFrame zurück oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`margin_right`](/slides/python-net/de/aspose.slides/itextframeformat/margin_right/) | Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`margin_top`](/slides/python-net/de/aspose.slides/itextframeformat/margin_top/) | Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`margin_bottom`](/slides/python-net/de/aspose.slides/itextframeformat/margin_bottom/) | Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`wrap_text`](/slides/python-net/de/aspose.slides/itextframeformat/wrap_text/) | **True**  wenn der Text an den Rändern des TextFrames umbrochen wird.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/de/aspose.slides/itextframeformat/anchoring_type/) | Gibt den vertikalen Ankertext in einem TextFrame zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`TextAnchorType`](/slides/python-net/de/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/de/aspose.slides/itextframeformat/center_text/) | Wenn NullableBool.True, dann sollte der Text horizontal im Feld zentriert werden.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/de/aspose.slides/itextframeformat/text_vertical_type/) | Bestimmt die Textausrichtung.<br/>            Der resultierende Wert der visuellen Textrotation, zusammengefasst aus dieser Eigenschaft und dem benutzerdefinierten Winkel<br/>            in der Eigenschaft RotationAngle.<br/>            Lesen/Schreiben [`TextVerticalType`](/slides/python-net/de/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/de/aspose.slides/itextframeformat/autofit_type/) | Gibt den Autofit-Modus des Textes zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`TextAutofitType`](/slides/python-net/de/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/de/aspose.slides/itextframeformat/column_count/) | Gibt die Anzahl der Spalten im Textbereich zurück oder legt sie fest.<br/>            Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf Null gesetzt. <br/>            Wert 0 bedeutet undefinierter Wert.<br/>            Lesen/Schreiben **int**. |
| [`column_spacing`](/slides/python-net/de/aspose.slides/itextframeformat/column_spacing/) | Gibt den Abstand zwischen Textspalten im Textbereich zurück oder legt ihn fest (in Punkten). Dies sollte nur gelten <br/>            wenn mehr als 1 Spalte vorhanden ist.<br/>            Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf Null gesetzt. <br/>            Lesen/Schreiben **float**. |
| [`three_d_format`](/slides/python-net/de/aspose.slides/itextframeformat/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekteigenschaften für einen Text darstellt.<br/>            Nur lesbar [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/de/aspose.slides/itextframeformat/keep_text_flat/) | Gibt zurück oder legt fest, dass der Text vollständig aus der 3D-Szene herausgehalten wird.<br/>            Lesen/Schreiben **bool**. |
| [`rotation_angle`](/slides/python-net/de/aspose.slides/itextframeformat/rotation_angle/) | Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb der Begrenzungsbox angewendet wird. Wenn sie nicht<br/>            angegeben ist, wird die Drehung der zugehörigen Form verwendet. Wenn sie angegeben ist, wird sie<br/>            unabhängig von der Form angewendet. Das bedeutet, dass die Form zusätzlich eine Drehung haben kann, während der Text selbst ebenfalls eine Drehung erhalten kann.<br/>            Der resultierende Wert der visuellen Textrotation, zusammengefasst aus dieser Eigenschaft und dem vordefinierten<br/>            vertikalen Typ in der Eigenschaft TextVerticalType.<br/>            Lesen/Schreiben **float**. |
| [`transform`](/slides/python-net/de/aspose.slides/itextframeformat/transform/) | Gibt die Textumbruchform zurück oder legt sie fest.<br/>            Lesen/Schreiben [`TextShapeType`](/slides/python-net/de/aspose.slides/textshapetype). |

## Methoden

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/de/aspose.slides/itextframeformat/get_effective/#) | Ermittelt die effektiven Textframe-Formatierungsdaten mit angewandter Vererbung. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)
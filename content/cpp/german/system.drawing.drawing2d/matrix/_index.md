---
title: Matrix
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt eine 3×3-Matrix dar, die Transformationsoperationen definiert. Objekte dieser Klasse sollten ausschließlich mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 118
url: /de/system.drawing.drawing2d/matrix/
---
## Matrix-Klasse

Stellt eine 3 × 3-Matrix dar, die Transformationsoperationen definiert. Objekte dieser Klasse sollten ausschließlich mit der Funktion [System::MakeObject()](../../system/makeobject/) allokiert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Matrix : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Erstellt eine Kopie des aktuellen Objekts. |
| void [Dispose](./dispose/)() | Setzt alle vom aktuellen Objekt erworbenen Betriebssystemressourcen frei. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Prüft, ob das angegebene Objekt ein [Matrix](./) ist und diesem Objekt identisch ist. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Gibt ein Array zurück, das die Elemente der Matrix in folgender Reihenfolge enthält: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Bestimmt, ob die vom aktuellen Objekt dargestellte Matrix eine Einheitsmatrix ist. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Bestimmt, ob die vom aktuellen Objekt dargestellte Matrix invertierbar ist. |
| **float** [get_OffsetX](./get_offsetx/)() const | Gibt den X-Translationswert der vom aktuellen Objekt dargestellten Matrix zurück. |
| **float** [get_OffsetY](./get_offsety/)() const | Gibt den Y-Translationswert der vom aktuellen Objekt dargestellten Matrix zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | Invertiert die vom aktuellen Objekt dargestellte Matrix. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| [Matrix](./matrix/)() | Konstruiert eine neue Instanz der Klasse [Matrix](./), die eine Einheitsmatrix darstellt. |
| [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Konstruiert eine neue Instanz der Klasse [Matrix](./) und initialisiert sie mit den angegebenen Werten. |
| [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Konstruiert eine neue Instanz der Klasse [Matrix](./) für die geometrische Transformation, die durch das angegebene Rechteck und das Punkt-Array definiert ist. |
| [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Konstruiert eine neue Instanz der Klasse [Matrix](./) für die geometrische Transformation, die durch das angegebene Rechteck und das Punkt-Array definiert ist. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Multipliziert die vom aktuellen Objekt dargestellte Matrix mit der angegebenen Matrix. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Multipliziert die vom aktuellen Objekt dargestellte Matrix mit der angegebenen Matrix. |
| [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt referenziell mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [Reset](./reset/)() | Setzt die vom aktuellen Objekt dargestellte Matrix zurück, sodass sie eine Einheitsmatrix wird. |
| void [Rotate](./rotate/)(**float**) | Dreht die vom aktuellen Objekt dargestellte Matrix im Uhrzeigersinn um den angegebenen Winkel. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Dreht die vom aktuellen Objekt dargestellte Matrix im Uhrzeigersinn um den Ursprung herum um den angegebenen Winkel. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Dreht die vom aktuellen Objekt dargestellte Matrix im Uhrzeigersinn um den angegebenen Punkt herum um den angegebenen Winkel. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Dreht die vom aktuellen Objekt dargestellte Matrix im Uhrzeigersinn um den angegebenen Punkt herum um den angegebenen Winkel. |
| void [Scale](./scale/)(**float**, **float**) | Wendet den angegebenen Skalierungsvektor auf die vom aktuellen Objekt dargestellte Matrix an. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Wendet den angegebenen Skalierungsvektor auf die vom aktuellen Objekt dargestellte Matrix an. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umstellen von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [Shear](./shear/)(**float**, **float**) | Wendet den angegebenen Scherungsvektor auf die vom aktuellen Objekt dargestellte Matrix an. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Wendet den angegebenen Scherungsvektor auf die vom aktuellen Objekt dargestellte Matrix an. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht das Konvertieren benutzerdefinierter Objekte in einen String. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Wendet die durch die vom aktuellen Objekt dargestellte Matrix definierte geometrische Transformation auf die angegebenen Punkte an. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Wendet die durch die vom aktuellen Objekt dargestellte Matrix definierte geometrische Transformation auf die angegebenen Punkte an. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Wendet die durch die vom aktuellen Objekt dargestellte Matrix definierte geometrische Transformation auf die angegebenen Punkte an. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Wendet die durch die vom aktuellen Objekt dargestellte Matrix definierte geometrische Transformation auf die angegebenen Punkte an. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Wendet nur die Skalierungs- und Rotationskomponenten der vom aktuellen Objekt dargestellten Matrix auf die angegebenen Punkte an. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Wendet nur die Skalierungs- und Rotationskomponenten der vom aktuellen Objekt dargestellten Matrix auf die angegebenen Punkte an. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Wendet nur die Skalierungs- und Rotationskomponenten der vom aktuellen Objekt dargestellten Matrix auf die angegebenen Punkte an. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Wendet nur die Skalierungs- und Rotationskomponenten der vom aktuellen Objekt dargestellten Matrix auf die angegebenen Punkte an. |
| void [Translate](./translate/)(**float**, **float**) | Wendet den angegebenen Translationsvektor auf die vom aktuellen Objekt dargestellte Matrix an. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Wendet den angegebenen Translationsvektor auf die vom aktuellen Objekt dargestellte Matrix an. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Multipliziert jeden Vektor in einem Array mit der vom aktuellen Objekt dargestellten Matrix. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Multipliziert jeden Vektor in einem Array mit der vom aktuellen Objekt dargestellten Matrix. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [~Matrix](./~matrix/)() | Destruktor. |
| virtual [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Drawing::Drawing2D](../)
* Bibliothek [Aspose.Slides](../../)
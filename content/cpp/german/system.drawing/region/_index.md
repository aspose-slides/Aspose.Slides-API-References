---
title: Region
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt das Innere einer grafischen Form dar. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 261
url: /de/system.drawing/region/
---
## Region Klasse

Stellt das Innere einer grafischen Form dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Umwickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Region : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Gibt eine Kopie des aktuellen Objekts zurück. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Ersetzt die von dem aktuellen Objekt dargestellte Region durch den Teil der Region, der durch das angegebene Rechteck definiert ist und nicht mit dieser Region überschneidet. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Ersetzt die von dem aktuellen Objekt dargestellte Region durch den Teil der Region, der durch das angegebene Rechteck definiert ist und nicht mit dieser Region überschneidet. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Ersetzt die von dem aktuellen Objekt dargestellte Region durch den Teil der Region, der durch den angegebenen Pfad definiert ist und nicht mit dieser Region überschneidet. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Ersetzt die von dem aktuellen Objekt dargestellte Region durch den Teil der angegebenen Region, der nicht mit dieser Region überschneidet. |
| void [Dispose](./dispose/)() | Gibt alle vom aktuellen Objekt erworbenen Betriebssystemressourcen frei. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Bestimmt, ob die angegebene Region identisch mit der vom aktuellen Objekt auf der angegebenen Zeichenfläche dargestellten Region ist. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-stilisierten Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-stilisierten Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis des Ausschlusses der durch das angegebene Rechteck definierten Region von ihr. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis des Ausschlusses der durch das angegebene Rechteck definierten Region von ihr. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis des Ausschlusses des durch den angegebenen Pfad definierten Bereichs. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis des Ausschlusses der angegebenen Region. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Gibt eine [RectangleF](../rectanglef/)-Struktur zurück, die ein Rechteck repräsentiert, das dieses [Region](./) auf der Zeichenfläche eines [Graphics](../graphics/)-Objekts begrenzt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Gibt ein RegionData-Objekt zurück, das die Daten enthält, die die vom aktuellen Objekt dargestellte Region definieren. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Gibt ein Array von [RectangleF](../rectanglef/)-Strukturen zurück, die dieses [Region](./) nach Anwendung der angegebenen Matrix-Transformation annähern. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis der Schnittmenge dieser Region und einer durch das angegebene Rechteck definierten Region. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis der Schnittmenge dieser Region und einer durch das angegebene Rechteck definierten Region. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis der Schnittmenge dieser Region und einer durch den angegebenen Pfad definierten Region. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis der Schnittmenge dieser Region und der angegebenen Region. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bestimmt, ob die vom aktuellen Objekt dargestellte Region auf der angegebenen Zeichenfläche ein leeres Innere hat. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bestimmt, ob die vom aktuellen Objekt dargestellte Region auf der angegebenen Zeichenfläche ein unendliches Innere hat. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Bestimmt, ob der angegebene Punkt innerhalb der vom aktuellen Objekt dargestellten Region liegt. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Bestimmt, ob der angegebene Punkt innerhalb der vom aktuellen Objekt dargestellten Region liegt. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Bestimmt, ob ein Teil des angegebenen Rechtecks innerhalb der vom aktuellen Objekt dargestellten Region liegt. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Bestimmt, ob ein Teil des angegebenen Rechtecks innerhalb der vom aktuellen Objekt dargestellten Region liegt. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bestimmt, ob der angegebene Punkt innerhalb der vom aktuellen Objekt dargestellten Region liegt, unter Verwendung der angegebenen Grafik. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bestimmt, ob der angegebene Punkt innerhalb der vom aktuellen Objekt dargestellten Region liegt, unter Verwendung der angegebenen Grafik. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Bestimmt, ob ein Teil des angegebenen Rechtecks innerhalb der vom aktuellen Objekt dargestellten Region liegt, unter Verwendung der angegebenen Grafik. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Bestimmt, ob ein Teil des angegebenen Rechtecks innerhalb der vom aktuellen Objekt dargestellten Region liegt, unter Verwendung der angegebenen Grafik. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Bestimmt, ob der angegebene Punkt innerhalb der vom aktuellen Objekt dargestellten Region liegt. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Bestimmt, ob der angegebene Punkt innerhalb der vom aktuellen Objekt dargestellten Region liegt, unter Verwendung der angegebenen Grafik. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| void [MakeEmpty](./makeempty/)() | Initialisiert das aktuelle Objekt zu einem leeren Inneren. |
| void [MakeInfinite](./makeinfinite/)() | Initialisiert dieses Region-Objekt zu einem unendlichen Inneren. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| [Region](./region/)() | Konstruiert eine neue Instanz der Klasse [Region](./). |
| [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Konstruiert eine neue Instanz der Klasse [Region](./), die eine durch das angegebene Rechteck definierte Region darstellt. |
| [Region](./region/)(const [Rectangle](../rectangle/)\&) | Konstruiert eine neue Instanz der Klasse [Region](./), die eine durch das angegebene Rechteck definierte Region darstellt. |
| [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Konstruiert eine neue Instanz der Klasse [Region](./), die eine durch den angegebenen Pfad definierte Region darstellt. |
| [Region](./region/)(const SkPath\&) |  |
| [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Konstruiert eine neue Instanz der Klasse [Region](./), die eine durch das angegebene RegionData-Objekt definierte Region darstellt. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines gemeinsamen). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Transformiert diese Region mittels der angegebenen Matrix. |
| void [Transform](./transform/)(const SkMatrix\&) | Transformiert diese Region mittels der angegebenen Matrix. |
| void [Translate](./translate/)(int, int) | Verschiebt die Koordinaten der Region um den angegebenen Betrag. |
| void [Translate](./translate/)(**float**, **float**) | Verschiebt die Koordinaten der Region um den angegebenen Betrag. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis der Vereinigungsoperation dieser Region und einer durch das angegebene Rechteck definierten Region. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis der Vereinigungsoperation dieser Region und einer durch das angegebene Rechteck definierten Region. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis der Vereinigungsoperation dieser Region und einer durch den angegebenen Pfad definierten Region. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch das Ergebnis der Vereinigungsoperation dieser Region und der angegebenen Region. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch die Teile dieser Region und der durch das angegebene Rechteck definierten Region, die nicht überschneiden. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch die Teile dieser Region und der durch das angegebene Rechteck definierten Region, die nicht überschneiden. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch die Teile dieser Region und des durch den angegebenen Pfad definierten Bereichs, die nicht überschneiden. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Ersetzt die vom aktuellen Objekt dargestellte Region durch die Teile dieser Region und der angegebenen Region, die nicht überschneiden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
| virtual  [~Region](./~region/)() | Destruktor. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)
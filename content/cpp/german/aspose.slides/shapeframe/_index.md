---
title: ShapeFrame
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Eigenschaften des Formrahmens dar.
type: docs
weight: 5136
url: /de/aspose.slides/shapeframe/
---
## ShapeFrame Klasse


Stellt die Eigenschaften des Formrahmens dar.

```cpp
class ShapeFrame : public Aspose::Slides::IShapeFrame
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Klont |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [CloneT](./clonet/)() override | Klont. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Gibt einen Wert zurück, der anzeigt, ob diese Instanz einem angegebenen Objekt gleich ist. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ShapeFrame](./)\>) | Gibt einen Wert zurück, der anzeigt, ob diese Instanz einem angegebenen Objekt gleich ist. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN gemäß IEC 60559:1989 keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN gemäß IEC 60559:1989 keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **float** [get_CenterX](./get_centerx/)() override | Gibt die X-Koordinate des Zentrums eines Rahmens zurück. Nur lesbar **float**. |
| **float** [get_CenterY](./get_centery/)() override | Gibt die Y-Koordinate des Zentrums eines Rahmens zurück. Nur lesbar **float**. |
| [NullableBool](../nullablebool/) [get_FlipH](./get_fliph/)() override | Bestimmt, ob ein Rahmen horizontal gespiegelt ist. Nur lesbar [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_FlipV](./get_flipv/)() override | Bestimmt, ob ein Rahmen vertikal gespiegelt ist. Nur lesbar [NullableBool](../nullablebool/). |
| **float** [get_Height](./get_height/)() override | Gibt die Höhe eines Rahmens zurück. Nur lesbar **float**. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() override | Gibt die Koordinaten eines Rahmens zurück. Nur lesbar [System::Drawing::RectangleF](../../system.drawing/rectanglef/). |
| **float** [get_Rotation](./get_rotation/)() override | Gibt die Anzahl der Grad zurück, um die ein Rahmen um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Nur lesbar **float**. |
| **float** [get_Width](./get_width/)() override | Gibt die Breite eines Rahmens zurück. Nur lesbar **float**. |
| **float** [get_X](./get_x/)() override | Gibt die X-Koordinate der oberen linken Ecke eines Rahmens zurück. Nur lesbar **float**. |
| **float** [get_Y](./get_y/)() override | Gibt die Y-Koordinate der oberen linken Ecke eines Rahmens zurück. Nur lesbar **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verbunden ist. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Gibt einen Hashcode für dieses Objekt zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Entspricht dem C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Entspricht dem C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Entspricht der C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
|  [ShapeFrame](./shapeframe/)(**float**, **float**, **float**, **float**, [NullableBool](../nullablebool/), [NullableBool](../nullablebool/), **float**) | Erstellt die Eigenschaften eines neuen Formrahmens. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Entspricht der C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Siehe auch

* Klasse [IShapeFrame](../ishapeframe/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)
---
title: Rotation3D
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die 3D-Drehung eines Diagramms dar.
type: docs
weight: 1327
url: /de/aspose.slides.charts/rotation3d/
---
## Rotation3D Klasse

Stellt die 3D-Drehung eines Diagramms dar.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück (zwischen 20 und 2000 Prozent). Lesen **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 und 500 Prozent). Lesen **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Gibt den Perspektivwert (Sichtfeldwinkel) für 3D-Diagramme zurück (zwischen 0 und 240). Wird ignoriert, wenn der Property-Wert RightAngleAxes true ist. Lesen **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch gezeichnet zu werden. Mit anderen Worten, es bestimmt, ob die Achsenwinkel des Diagramms unabhängig von Diagrammdrehung oder -neigung sind. Lesen **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Gibt den Rotationsgrad um die X-Achse zurück, d.h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Property entspricht dem Eintrag 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option "Y Rotation" in PowerPoint 2007+. Lesen **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Gibt den Rotationsgrad um die Y-Achse zurück, d.h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Property entspricht dem Eintrag 21.2.2.158 rotY (Y Rotation) in ECMA-376 und der Option "X Rotation" in PowerPoint 2007+. Lesen **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zu C# [Object.GetHashCode()](../../system/object/gethashcode/) Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zu C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzweise ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Setzt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite (zwischen 20 und 2000 Prozent). Schreiben **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 und 500 Prozent). Schreiben **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Setzt den Perspektivwert (Sichtfeldwinkel) für 3D-Diagramme (zwischen 0 und 240). Wird ignoriert, wenn der Property-Wert RightAngleAxes true ist. Schreiben **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch gezeichnet zu werden. Mit anderen Worten, es bestimmt, ob die Achsenwinkel des Diagramms unabhängig von Diagrammdrehung oder -neigung sind. Schreiben **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Setzt den Rotationsgrad um die X-Achse, d.h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Property entspricht dem Eintrag 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option "Y Rotation" in PowerPoint 2007+. Schreiben **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Setzt den Rotationsgrad um die Y-Achse, d.h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Property entspricht dem Eintrag 21.2.2.158 rotY (Y Rotation) in ECMA-376 und der Option "X Rotation" in PowerPoint 2007+. Schreiben **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines gemeinsamen). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zu C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/)) Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IRotation3D](../irotation3d/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)
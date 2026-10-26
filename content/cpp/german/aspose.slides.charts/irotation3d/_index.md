---
title: IRotation3D
second_title: Aspose.Slides für C++ API Referenz
description: Stellt die 3D-Drehung eines Diagramms dar.
type: docs
weight: 1171
url: /de/aspose.slides.charts/irotation3d/
---
## IRotation3D Klasse


Repräsentiert 3D-Drehung eines Diagramms.

```cpp
class IRotation3D : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück (zwischen 20 und 2000 Prozent). Lesen **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 und 500 Prozent). Lesen **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | Gibt den Perspektivwert (Sichtfeldwinkel) für 3D-Diagramme zurück (zwischen 0 und 100). Ignoriert, wenn der Wert der Eigenschaft RightAngleAxes true ist. Lesen **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch gezeichnet zu werden. Mit anderen Worten, sie bestimmt, ob die Achsenwinkel unabhängig von Diagrammdrehung oder -neigung sind. Lesen **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | Gibt den Rotationsgrad um die X-Achse zurück, d. h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Eigenschaft entspricht dem Eintrag 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option "Y Rotation" in PowerPoint 2007+. Lesen **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Gibt den Rotationsgrad um die Y-Achse zurück, d. h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Eigenschaft entspricht dem Eintrag 21.2.2.158 rotY (Y Rotation) in ECMA-376 und der Option "X Rotation" in PowerPoint 2007+. Lesen **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ruft den tatsächlichen Typ des Objekts ab. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht nach Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | Legt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 20 und 2000 Prozent). Schreiben **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 und 500 Prozent). Schreiben **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | Legt den Perspektivwert (Sichtfeldwinkel) für 3D-Diagramme fest (zwischen 0 und 100). Ignoriert, wenn der Wert der Eigenschaft RightAngleAxes true ist. Schreiben **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch gezeichnet zu werden. Mit anderen Worten, sie bestimmt, ob die Achsenwinkel unabhängig von Diagrammdrehung oder -neigung sind. Schreiben **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | Legt den Rotationsgrad um die X-Achse fest, d. h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Eigenschaft entspricht dem Eintrag 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option "Y Rotation" in PowerPoint 2007+. Schreiben **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Legt den Rotationsgrad um die Y-Achse fest, d. h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Eigenschaft entspricht dem Eintrag 21.2.2.158 rotY (Y Rotation) in ECMA-376 und der Option "X Rotation" in PowerPoint 2007+. Schreiben **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt geteiltem). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des geteilten Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smarte Zeiger oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen smarte Zeiger oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smarte Zeiger oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smarte Zeiger oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)
---
title: PictureFrameLock
second_title: Aspose.Slides für C++ API Referenz
description: Bestimmt, welche Vorgänge am übergeordneten PictureFrame deaktiviert sind.
type: docs
weight: 4746
url: /de/aspose.slides/pictureframelock/
---
## PictureFrameLock Klasse

Bestimmt, welche Operationen am übergeordneten [PictureFrame](../pictureframe/) deaktiviert sind.

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-Stil Fließkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-Stil Fließkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Bestimmt, ob das Ändern von Anpassungswerten verboten ist. Lese **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Bestimmt, ob das Ändern von Pfeilspitzen verboten ist. Lese **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Bestimmt, ob eine Form beim Skalieren das Seitenverhältnis beibehalten muss. Lese **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | Bestimmt, ob das Zuschneiden eines Bildes verboten ist. Lese **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Bestimmt, ob eine direkte Änderung der Kontur dieser Form verboten ist. Lese **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Bestimmt, ob das Hinzufügen dieser Form zu einer Gruppe verboten ist. Lese **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Gibt true zurück, wenn alle Sperr-Flags deaktiviert sind. Nur-Lese **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Bestimmt, ob das Verschieben dieser Form verboten ist. Lese **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Bestimmt, ob das Ändern des Rotationswinkels dieser Form verboten ist. Lese **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Bestimmt, ob das Auswählen dieser Form verboten ist. Lese **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Bestimmt, ob das Ändern des Formtyps verboten ist. Lese **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Bestimmt, ob das Ändern der Größe dieser Form verboten ist. Lese **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die mit dem Objekt verbundene Referenzzähler-Datenstruktur. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren einer C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächter-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Bestimmt, ob das Ändern von Anpassungswerten verboten ist. Schreibe **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Bestimmt, ob das Ändern von Pfeilspitzen verboten ist. Schreibe **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Bestimmt, ob eine Form beim Skalieren das Seitenverhältnis beibehalten muss. Schreibe **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | Bestimmt, ob das Zuschneiden eines Bildes verboten ist. Schreibe **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Bestimmt, ob eine direkte Änderung der Kontur dieser Form verboten ist. Schreibe **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Bestimmt, ob das Hinzufügen dieser Form zu einer Gruppe verboten ist. Schreibe **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Bestimmt, ob das Verschieben dieser Form verboten ist. Schreibe **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Bestimmt, ob das Ändern des Rotationswinkels dieser Form verboten ist. Schreibe **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Bestimmt, ob das Auswählen dieser Form verboten ist. Schreibe **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Bestimmt, ob das Ändern des Formtyps verboten ist. Schreibe **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Bestimmt, ob das Ändern der Größe dieser Form verboten ist. Schreibe **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Erlaubt das Umstellen von Zeigern in Containern auf den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren einer C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächter-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [BaseShapeLock](../baseshapelock/)
* Klasse [IPictureFrameLock](../ipictureframelock/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)
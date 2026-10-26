---
title: IPictureFrameLock
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, welche Vorgänge im übergeordneten PictureFrameEx deaktiviert sind.
type: docs
weight: 3264
url: /de/aspose.slides/ipictureframelock/
---
## IPictureFrameLock Klasse

Bestimmt, welche Vorgänge im übergeordneten PictureFrameEx deaktiviert sind.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Bestimmt, ob das Ändern von Adjustierungswerten verboten ist. Lese **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Bestimmt, ob das Ändern von Pfeilspitzen verboten ist. Lese **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Bestimmt, ob eine Form beim Skalieren das Seitenverhältnis beibehalten muss. Lese **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | Bestimmt, ob das Zuschneiden eines Bildes verboten ist. Lese **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Bestimmt, ob das direkte Ändern der Kontur dieser Form verboten ist. Lese **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bestimmt, ob das Hinzufügen dieser Form zu einer Gruppe verboten ist. Lese **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Gibt true zurück, wenn alle Sperr-Flags deaktiviert sind. Nur-Lese **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Bestimmt, ob das Verschieben dieser Form verboten ist. Lese **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Bestimmt, ob das Ändern des Rotationswinkels dieser Form verboten ist. Lese **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bestimmt, ob das Auswählen dieser Form verboten ist. Lese **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Bestimmt, ob das Ändern des Formtyps verboten ist. Lese **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bestimmt, ob das Skalieren dieser Form verboten ist. Lese **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analogie zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analogie zum C#-„is“-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert die C#-lock()-Anweisung zum Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Bestimmt, ob das Ändern von Adjustierungswerten verboten ist. Schreibe **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Bestimmt, ob das Ändern von Pfeilspitzen verboten ist. Schreibe **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Bestimmt, ob eine Form beim Skalieren das Seitenverhältnis beibehalten muss. Schreibe **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | Bestimmt, ob das Zuschneiden eines Bildes verboten ist. Schreibe **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Bestimmt, ob das direkte Ändern der Kontur dieser Form verboten ist. Schreibe **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bestimmt, ob das Hinzufügen dieser Form zu einer Gruppe verboten ist. Schreibe **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Bestimmt, ob das Verschieben dieser Form verboten ist. Schreibe **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Bestimmt, ob das Ändern des Rotationswinkels dieser Form verboten ist. Schreibe **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bestimmt, ob das Auswählen dieser Form verboten ist. Schreibe **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Bestimmt, ob das Ändern des Formtyps verboten ist. Schreibe **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bestimmt, ob das Skalieren dieser Form verboten ist. Schreibe **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des geteilten Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert die C#-lock()-Anweisung zum Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IBaseShapeLock](../ibaseshapelock/)
* Namespace [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)
---
title: ViewProperties
second_title: Aspose.Slides für C++ API-Referenz
description: Präsentationsweite Ansichtseigenschaften.
type: docs
weight: 5565
url: /de/aspose.slides/viewproperties/
---
## ViewProperties Klasse

[Presentation](../presentation/) weite Ansichtseigenschaften.

```cpp
class ViewProperties : public Aspose::Slides::IViewProperties,
                       public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschliesslich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschliesslich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **float** [get_GridSpacing](./get_gridspacing/)() override | Gibt den Gitterabstand zurück, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden sollte. Lese **float**. |
| [ViewType](../viewtype/) [get_LastView](./get_lastview/)() override | Gibt den Ansichtsmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. Lese [ViewType](../viewtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewProperties](../inormalviewproperties/)\> [get_NormalViewProperties](./get_normalviewproperties/)() override | Stellt normale Ansichtseigenschaften dar. Die normale Ansicht besteht aus drei Inhaltsbereichen: der Folie selbst, einem Seiteninhaltbereich und einem unteren Inhaltsbereich. Nur lesbar [INormalViewProperties](../inormalviewproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommonSlideViewProperties](../icommonslideviewproperties/)\> [get_NotesViewProperties](./get_notesviewproperties/)() override | Gibt gemeinsame Ansichtseigenschaften an, die mit dem Notizansichtsmodus verbunden sind. Nur lesbar [ICommonSlideViewProperties](../icommonslideviewproperties/). |
| [NullableBool](../nullablebool/) [get_ShowComments](./get_showcomments/)() override | Gibt an, ob die Folienkommentare angezeigt werden sollen. Lese [NullableBool](../nullablebool/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommonSlideViewProperties](../icommonslideviewproperties/)\> [get_SlideViewProperties](./get_slideviewproperties/)() override | Gibt gemeinsame Ansichtseigenschaften an, die mit dem Folienansichtsmodus verbunden sind. Nur lesbar [ICommonSlideViewProperties](../icommonslideviewproperties/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_GridSpacing](./set_gridspacing/)(**float**) override | Setzt den Gitterabstand, der für das dem Präsentationsdokument zugrunde liegende Raster in Punkten verwendet werden soll. Schreibe **float**. |
| void [set_LastView](./set_lastview/)([ViewType](../viewtype/)) override | Gibt den Ansichtsmodus an, der beim letzten Speichern des Präsentationsdokuments verwendet wurde. Schreibe [ViewType](../viewtype/). |
| void [set_ShowComments](./set_showcomments/)([NullableBool](../nullablebool/)) override | Gibt an, ob die Folienkommentare angezeigt werden sollen. Schreibe [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert die Entsperrung des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IViewProperties](../iviewproperties/)
* Klasse [IDOMObject](../idomobject/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)
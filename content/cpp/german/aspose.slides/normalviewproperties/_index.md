---
title: NormalViewProperties
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt die Eigenschaften der Normalansicht dar. Die Normalansicht besteht aus drei Inhaltsbereichen: der Folie selbst, einem seitlichen Inhaltsbereich und einem unteren Inhaltsbereich."
type: docs
weight: 4525
url: /de/aspose.slides/normalviewproperties/
---
## NormalViewProperties Klasse

Stellt die Eigenschaften der Normalansicht dar. Die Normalansicht besteht aus drei Inhaltsbereichen: der Folie selbst, einem seitlichen Inhaltsbereich und einem unteren Inhaltsbereich.

```cpp
class NormalViewProperties : public Aspose::Slides::INormalViewProperties
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztypobjekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttypobjekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert C#-artige Gleitkomma-Vergleiche, bei denen zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert C#-artige Gleitkomma-Vergleiche, bei denen zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() override | Gibt den Zustand an, in dem die horizontale Trennleiste angezeigt werden soll. Eine horizontale Trennleiste trennt die Folie vom Inhaltsbereich unterhalb der Folie. |
| **bool** [get_PreferSingleView](./get_prefersingleview/)() override | Gibt an, ob der Benutzer eine Vollfenster-Einzel-Inhaltsregion anstelle der Standard-Normalansicht mit drei Inhaltsbereichen bevorzugt. Ist dies aktiviert, kann die Anwendung einen der Inhaltsbereiche im gesamten Fenster anzeigen. Lesen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() override | Dieses Element gibt die Größe des seitlichen Inhaltsbereichs der Normalansicht an, wenn der Bereich eine variable wiederhergestellte Größe (weder minimiert noch maximiert) hat. Nur lesen [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() override | Dieses Element gibt die Größe des oberen Folienbereichs der Normalansicht an, wenn der Bereich eine variable wiederhergestellte Größe (weder minimiert noch maximiert) hat. Nur lesen [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() override | Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Gliederungsinhalte in einem der Inhaltsbereiche der Normalansicht angezeigt werden. Lesen **bool**. |
| **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() override | Gibt an, ob die vertikale Trennleiste bei ausreichend kleiner seitlicher Region in den minimierten Zustand einrasten soll. Lesen **bool**. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() override | Gibt den Zustand an, in dem die vertikale Trennleiste angezeigt werden soll. Eine vertikale Trennleiste trennt die Folie vom seitlichen Inhaltsbereich. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zu C# [Object.GetHashCode()](../../system/object/gethashcode/) Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zu C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-lock()-Statement zum Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zu C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von abgeleiteten Klassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von abgeleiteten Klassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttypobjekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | Gibt den Zustand an, in dem die horizontale Trennleiste angezeigt werden soll. Eine horizontale Trennleiste trennt die Folie vom Inhaltsbereich unterhalb der Folie. |
| void [set_PreferSingleView](./set_prefersingleview/)(**bool**) override | Gibt an, ob der Benutzer eine Vollfenster-Einzel-Inhaltsregion anstelle der Standard-Normalansicht mit drei Inhaltsbereichen bevorzugt. Ist dies aktiviert, kann die Anwendung einen der Inhaltsbereiche im gesamten Fenster anzeigen. Schreiben **bool**. |
| void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) override | Gibt an, ob die Anwendung Symbole anzeigen soll, wenn Gliederungsinhalte in einem der Inhaltsbereiche der Normalansicht angezeigt werden. Schreiben **bool**. |
| void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) override | Gibt an, ob die vertikale Trennleiste bei ausreichend kleiner seitlicher Region in den minimierten Zustand einrasten soll. Schreiben **bool**. |
| void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | Gibt den Zustand an, in dem die vertikale Trennleiste angezeigt werden soll. Eine vertikale Trennleiste trennt die Folie vom seitlichen Inhaltsbereich. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt einem geteilten). Ermöglicht das Wechseln von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zu C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/)) Ausdruck. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C#-lock()-Statement zum Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Bemerkungen

Das folgende Beispiel zeigt, wie die [ViewProperties::get_NormalViewProperties](../viewproperties/get_normalviewproperties/)-Eigenschaften einer PowerPoint [Presentation](../presentation/) konfiguriert werden können. 
```cpp
// Instanziiere ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto normalViewProperties = pres->get_ViewProperties()->get_NormalViewProperties();

normalViewProperties->set_HorizontalBarState(SplitterBarStateType::Restored);
normalViewProperties->set_VerticalBarState(SplitterBarStateType::Maximized);
normalViewProperties->get_RestoredTop()->set_AutoAdjust(true);
normalViewProperties->get_RestoredTop()->set_DimensionSize(80.0f);
normalViewProperties->set_ShowOutlineIcons(true);
pres->Save(u"presentation_normal_view_state.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [INormalViewProperties](../inormalviewproperties/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)
---
title: ParagraphFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Diese Klasse enthält die Absatzformatierungseigenschaften. Im Gegensatz zu IParagraphFormatEffectiveData sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 4668
url: /de/aspose.slides/paragraphformat/
---
## ParagraphFormat Klasse

This class contains the paragraph formatting properties. Unlike [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), all properties of this class are writeable.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Methoden

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergleicht mit dem angegebenen Objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitpunktvergleich, wobei zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitpunktvergleich, wobei zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück. Siehe [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Gibt die Standardtabulationsgröße ohne Vererbung zurück. Siehe **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Ermittelt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Gibt die Schriftart-Ausrichtung in einem Absatz ohne Vererbung zurück. Siehe [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Gibt den Erstzeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück. Der hängende Einzug kann mit negativen Werten definiert werden. Siehe **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Ermittelt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Gibt den linken Rand in einem Absatz ohne Vererbung zurück. Siehe **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück. Siehe **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Gibt das Objekt Parent_Immediate zurück. Nur-Lesen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Gibt das übergeordnete [IPresentationComponent](../ipresentationcomponent/) zurück. Nur-Lesen [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Ermittelt, ob die Rechts-zu-Links-Schreibung in einem Absatz verwendet wird. Keine Vererbung angewendet. Siehe [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Siehe **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Siehe **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück. Positiver Wert bedeutet Prozentsatz, negativer - Größe in Punkten. Keine Vererbung angewendet. Siehe **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Gibt die Tabulation eines Absatzes am angegebenen Index zurück. Keine Vererbung angewendet. Nur-Lesen [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Gibt die Tabulationen eines Absatzes zurück. Keine Vererbung angewendet. Nur-Lesen [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Ermittelt die effektiven Absatzformatierungsdaten mit angewandter Vererbung. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Gibt den Hash-Code zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-Anweisung lock(). Direkt aufrufen oder das Sentinelle-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [ParagraphFormat](./paragraphformat/)() | Initialisiert eine neue Instanz der Klasse [ParagraphFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt referenziell mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsam genutzten Referenzzähler um den angegebenen Wert. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Setzt die Textausrichtung in einem Absatz ohne Vererbung. Schreiben [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Setzt die Standardtabulationsgröße ohne Vererbung. Schreiben **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Ermittelt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Setzt die Schriftart-Ausrichtung in einem Absatz ohne Vererbung. Schreiben [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Setzt den Erstzeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung. Der hängende Einzug kann mit negativen Werten definiert werden. Schreiben **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Ermittelt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Setzt den linken Rand in einem Absatz ohne Vererbung. Schreiben **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Setzt den rechten Rand in einem Absatz ohne Vererbung. Schreiben **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Ermittelt, ob die Rechts-zu-Links-Schreibung in einem Absatz verwendet wird. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Setzt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Schreiben **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Setzt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum haben soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Schreiben **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Setzt den Abstand zwischen Grundlinien in einem Absatz. Positiver Wert bedeutet Prozentsatz, negativer - Größe in Punkten. Keine Vererbung angewendet. Schreiben **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsam genutzten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsam genutzten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsam genutzten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-Anweisung lock(). Direkt aufrufen oder das Sentinelle-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Bemerkungen

Diese Klasse wird verwendet, um die für einen bestimmten Absatz definierten Absatzeigenschafts-Formate zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die "undefiniert" bedeuten.

Um die effektiven Werte der Formatierungsparameter einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [ParagraphFormat::GetEffective](./geteffective/) verwenden, die eine Instanz von [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) zurückgibt.

## Siehe auch

* Klasse [PVIObject](../pviobject/)
* Klasse [IParagraphFormat](../iparagraphformat/)
* Klasse [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Namensraum [Aspose::Slides](../)
* Library [Aspose.Slides](../../)